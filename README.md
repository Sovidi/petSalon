# petSalon

![chrome-capture-2024-1-23](https://github.com/Sovidi/petSalon/assets/133857264/3c42d08a-cf81-436c-9443-2179e3c12f5e)



### 소개

> 위치기반 애견 및 애묘 디자이너 탐색 어플입니다.
> 

### 사용기술

![](https://img.shields.io/badge/javascript-F7DF1E.svg?&style=for-the-badge&logo=javascript&logoColor=ffffff)
![](https://img.shields.io/badge/css3-1572B6.svg?&style=for-the-badge&logo=css3&logoColor=ffffff)
![](https://img.shields.io/badge/sass-CC6699.svg?&style=for-the-badge&logo=sass&logoColor=ffffff)
![](https://img.shields.io/badge/html5-E34F26.svg?&style=for-the-badge&logo=html5&logoColor=ffffff)
![](https://img.shields.io/badge/mongodb-47A248.svg?&style=for-the-badge&logo=mongodb&logoColor=ffffff)
![](https://img.shields.io/badge/next.js-000000.svg?&style=for-the-badge&logo=nextdotjs&logoColor=ffffff)
![](https://img.shields.io/badge/VScode-007ACC.svg?&style=for-the-badge&logo=visualstudiocode&logoColor=ffffff)

### 개발기간

> 2023.12.01 ~ 2024.01.15
> 

### 개발환경

- Visual Studio Code
- Next.js
- SCSS
- HTML

### 플러그인
- MySQL
- MongoDB
- KakapMap
- Swiper
- CloudType

### 개발이슈

> 본래 MySQL 로 구축중에 있었으나 MongoDB 로 선향하였습니다.

> Next.js 를 통해 엔드포인트를 내장하였습니다. 서버사이드 렌더링을 최대한 응용하기위한 프레임워크 선정입니다.

> 핸드폰의 위치기반 접근과, 현재 위도 경도에 해당하는 도로명 주소 추출, 그리고 현재 위치 기반으로 일정거리 안에서만 게시물이 보이게 하는 공식을 사용하여 위치기반 매칭을 구현하였습니다.

> 저는 마이페이지 및 회원관리 데이터 및 입력시스템을 설계하였습니다. 과정에서 데이터 불러오기 및 시점 이슈와 여러 항목으로 나누어지는 데이터를 하나의 오브젝트로 통합관리하는 방법을 고안 하였습니다. 프로필 사진은 프롭 형태로 저장하여 데이터베이스에 저장하며 뿐만아닌 회원데이터 각각을 데이터베이스에 안정적으로 저장하고 다른 컴포넌트에서 다른 개발팀원이 데이터를 온전히 사용할 수 있도록 연결하는 역할을 하였습니다.

> 현재 나의 데이터가 있다면 수정 input 에 value 값으로 놓여지며 수정시에 참조할 수 있도록 하는 기능으로 추후 수정하였습니다. 본래 회원 데이터를 State 에 담고 그 데이터를 따로 스트링으로 빼고 수정하는 이중 교환 형식을 지녔었으나, 이미 회원 데이터가 서버에서 불러와져 있다는 것을 인지하고, 데이터 자체를 input 에서 읽을 수 있게 고안하여 수정했습니다.

> MongoDB 서버 연결 코드를 핵심변수 구조분해 반환형식으로 만들고 다른 서버 컴포넌트별로 이 중앙코드를 불러와 서버연결할 수 있도록 하여 팀원들이 서버 코드를 쉽게 작성할 수 있도록 하였습니다.
