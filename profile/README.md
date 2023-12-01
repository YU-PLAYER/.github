# SportsPie

## :hand: Introduce

&nbsp; **SportsPie**는 축구를 좋아하고 사랑하는 이들을 위한 만남의 장을 제공합니다. 간편한 경기 생성, 참여 신청 및 취소, 전적 관리 등의 기능을 제공합니다.

## :soccer: Core Feature

- 경기 생성 및 참여
- 전적 조회 및 관리
- 경기 일정 리마인드

## :heart: How to Use

### Service Domain

- [http://www.sportspie.xyz/](http://www.sportspie.xyz/)

### Explanation

<img width="411" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/e982f35e-de0b-4bfe-833d-b63286179829">

- `메인 페이지` : 
  - 배너 : 배너에서 축구 관련 대회정보를 확인할 수 있다.
  - 생성된 경기 확인 : 날짜 슬라이더를 이용하여 날짜별 생성된 경기를 확인할 수 있다. 최신순/과거순의 정렬 기능과 제목 검색 기능은 사용자가 부가적으로 선택할 수 있다.
  - 하단 네비게이션 바 : 1, 2, 4, 5 버튼을 클릭하였을 때 로그인이 되어 있지 않을 경우 경고 메시지를 출력하고 로그인 페이지로 이동한다.

    <img width="300" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/08336c8b-e625-4f41-aaa9-ab52c3000e15">

    1. `지도 페이지` 이동
    2. `경기 글 작성 페이지` 이동
    3. `메인 페이지` 이동
    4. `내 경기 목록 페이지` 이동
    5. `사용자 본인 프로필 페이지` 이동

<img width="411" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/5e19dd33-a9d0-4c82-8c52-33aa9b64c5bc">

- `사용자 본인 프로필 페이지` : 사용자 본인의 프로필 사진, 사용자 정보, 상태 메세지, 선호 포지션, 전적 정보가 표시되며 공지사항, 안전정보, 신고하기, 프로필 수정 페이지로 이동하는 링크가 있고 로그아웃 버튼과 회원탈퇴 버튼이 있다.

<img width="412" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/354e9fcb-8647-4c5f-bf00-93741dfcfb30">

- `사용자 본인 프로필 수정 페이지` : 사용자 본인의 프로필 사진, 사용자 정보, 상태 메세지, 선호 포지션, 전적 정보를 수정할수 있으며 자신의 프로필 사진, 사용자 정보, 상태 메세지, 전적 정보를 다른 사용자에게 공개할지 말지 공개여부를 선택할 수 있다.

<img width="411" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/0b4465a6-0ed1-4be3-8993-c1738d5b6a49">

- `다른 사용자 프로필 페이지` : 자신이 열람하고싶은 사용자의 프로필 정보 공개여부에 따라 프로필 사진, 사용자 정보, 상태 메세지, 전적 정보가 각각 표시되거나 표시되지않지만 선호 포지션은 항상 표시된다.

<img width="412" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/914b1fcb-f83f-4600-8677-b65da18c2e92">

- `경기글 상세페이지` : 경기글의 제목, 경기장 이름과 사진, 최대 경기 인원, 경기 시작 시간, 경기 당일 날씨, 경기 상세 내용글, 팀을 선택할수있는 팀 선택UI이 있으며 사용자는 신청하기 버튼을 통해 원하는 팀에 신청할 수 있고 취소하기 버튼을 통해 신청을 취소할 수 있다. 또한 경기글을 작성한 작성자에게는 인원확정 버튼과 결과확정 버튼, 그리고 삭제하기 버튼이 추가로 존재한다.

<img width="411" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/94389245-4533-4a2f-af0b-837b2cdc81e9">

- `로그인 페이지` : 소셜 계정(구글/네이버/카카오)을 이용하여 로그인할 수 있는 기능이다.

<img width="413" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/c3c338b7-b8c0-417d-bff3-177a46fe1131">

- `인원 모집글 작성 페이지` : 제목 / 최대 참여 인원수 / 경기날짜 및 시간 / 경기장소 / 상세내역을 입력하여 경기글을 작성할 수 있는 기능이다.

<img width="411" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/ea70c9f7-14d7-4376-b24c-b12f806c9f0d">

- `내 경기목록 확인 페이지` : 사용자가 자신이 참여한 경기목록들을 확인할 수 있는 페이지이다. 예정된 경기에서는 경기가 시작되지 않는 경기로 인원이 모집중인 예정경기와 인원이 모두 확정된 확정경기를 종료된 경기에서는 경기가 시작된 경기들로 결과 미확정, 승리, 패배, 무승부 경기를 확인할 수 있다. 전체 경기는 이 모든 경기가 포함되며 사용자는 배너에서 자신이 원하는 경기 목록을 선택하여 확인할 수 있다.
내 주변 경기장 확인 페이지 : 사용자 위치를 중심으로 10Km 내에 위치한 경기장을 표시하여 사용자에게 경기장 정보를 제공하는 페이지이다.

<img width="411" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/4cefc65e-1705-40fa-86a6-fdd0366a770c">

- `공지사항 페이지` : 웹 사이트 이용과 관련된 공지 내역을 확인할 수 있는 기능이다.

<img width="410" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/6e45fc7b-9ef4-4c0e-9043-2a7cc1557037">

- `안전정보 페이지` : 경기 간 발생할 수 있는 안전사고를 예방하고 알려주기 위한 기능이다.

<img width="413" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/e16bb8fe-9915-4bbb-b1c9-e279aef52413">

- `신고하기 페이지` : 사용자가 경기 종료 후 비매너 유저를 신고할 수 있는 페이지다.

<img width="411" alt="image" src="https://github.com/YU-PLAYER/.github/assets/68031450/764ec757-fd13-41d5-961a-fd66fd8e5659">

- `알림` : 참가 신청한 경기가 확정되었거나 경기 결과가 확정되었을 때, 경기 하루 전날 사용자에게 알림을 전달해 주는 기능이다.

## :hammer: Tech Stack

<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=black"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=Terraform&logoColor=white"> <img src="https://img.shields.io/badge/Naver Cloud Platform-03C75A?style=for-the-badge&logo=Naver&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white">

## :file_folder: Repository

- [Front-End](https://github.com/YU-PLAYER/sportspie-web)
- [Back-End](https://github.com/YU-PLAYER/sportspie-was)
- [IaC](https://github.com/YU-PLAYER/sportspie-terraform)

## :information_desk_person: Team Member

<table>
    <thead>
        <tr>
            <th colspan="3">Front-End</th>
            <th colspan="3">Back-End</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center"><a href="https://github.com/PMS990126">박민성</a></td>
            <td align="center"><a href="https://github.com/YujinB">백유진</a></td>
            <td align="center"><a href="https://github.com/Din0lee">이승현</a></td>
            <td align="center"><a href="https://github.com/nurugji">김진학 (팀장)</a></td>
            <td align="center"><a href="https://github.com/HyeonjunOh">오현준</a></td>
            <td align="center"><a href="https://github.com/jinlee1703">이진우</a></td>
        </tr>
        <tr>
            <td><a href="https://github.com/PMS990126"><img src="https://avatars.githubusercontent.com/u/127314376" width="90px" height="90px"/></a></td>
            <td><a href="https://github.com/YujinB"><img src="https://avatars.githubusercontent.com/u/121761705" width="90px" height="90px"/></a></td>
            <td><a href="https://github.com/Din0lee"><img src="https://avatars.githubusercontent.com/u/96680128" width="90px" height="90px"/></a></td>
            <td><a href="https://github.com/nurugji"><img src="https://avatars.githubusercontent.com/u/75533765" width="90px" height="90px"/></a></td>
            <td><a href="https://github.com/HyeonjunOh"><img src="https://avatars.githubusercontent.com/u/57754849" width="90px" height="90px"/></a></td>
            <td><a href="https://github.com/jinlee1703"><img src="https://avatars.githubusercontent.com/u/68031450" width="90px" height="90px"/></a></td>
        </tr>
    </tbody>
</table>
