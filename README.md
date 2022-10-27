# 개인 프로젝트 - 직업 훈련 서비스 커뮤니티 게시판 가제:(YearBook)

## 목표 - 직업 훈련과 관련된 서비스를 편리하게 제공하는 API 

### 🔍 진행방식

- 프로젝트는 **TODOLIST, API 사용 설명서, 프로젝트 진행 유의사항** 세 가지로 구성되어 있다.
- TODOLIST 를 꾸준히 업데이트하려 노력한다. 
- 특히 기능을 구현하기 전에 기능 목록을 만들고, 기능 단위로 커밋 하는 방식으로 진행한다.
- API 사용설명서를 제작하여 내가 만드는 서비스에 대해 확실하게 이해한다.
- 기본 명제로는 기능 세분화, RESTful API 유지, 배포까지 고려한 제대로 된 프로젝트 기획할 것.

### ⌨ 프로젝트 기록 방법

- 내 경우 나의 git repository에 지속적인 관리 예정.

### TODOLIST

0. 웹 서비스 개요 설계하기(최소안 도출)
    1. [x] 서비스 정의 - 내가 구현하고자 하는 서비스란?
        - [x] 요약 : 직업 학원의 콘텐츠 중개 커뮤니티 서비스
        - [x] 설명 : 학원, 강사, 학생 간에서 이뤄지는 커뮤니티를 활성화 시켜주는 플랫폼으로서의 역할을 한다.
        - [x] 구성 : 학원은 공간을 구성하여 취업과 관련된 콘텐츠를 제공해야 하며, 강사는 콘텐츠의 생산자, 학생은 콘텐츠의 이용자로 정의할 수 있다.

    2. 벤치마크 
        - [] 토스 : [링크](https://toss.im/new-dimension/brand-story)
            - [x] 이유 : 주요 사용자를 위한 디자인 시스템이 잘 되어있다. 사용자는 모바일을 통해 편리하게 이용하기를 원하고, 단순하고 직관적인 디자인을 통해 사용자 경험을 극대화 하는 방향성을 추구하고 있다. 이를 벤치마킹 하여 서비스 방향성 및 디자인을 구성하고자 한다.
        - []원티드 : [링크](https://www.wanted.co.kr/)
            - [x]이유 : 내가 관심을 가졌던 취업과 관련한 정보를 다루기도 하고, 정보설계에 대한 좋은 참고서가 될 것 같다.
            - [x]검색 : 원티드의 메뉴 디자인에 대한 참고 글을 보았다 [링크](https://brunch.co.kr/@66c669db056d4f7/15)


    3. [x] 사용자 정의 - 기본 사용자는 3종류의 유형을 가지고 있다.(학원,강사,학생)
        - [x]학원 : 홈페이지 서비스의 운영자이다. 서비스 내에서 강의실을 개설할 수 있으며, 강의실에 소속된 강사와 학생은 그 안에서 서비스를 이용할 수 있다.
        - [x]강사 : 홈페이지 서비스의 이용자이다. 학원을 통해 강의실에 배치되어 게시판을 이용할 수 있다. 기본적인 콘텐츠를 제공하는 제공자이며 학생들은 콘텐츠를 활용하여 과제 제출등을 할 수 있다.
        - [x]학생 : 홈페이지 서비스의 이용자이다. 학원을 통해 강의실에 배치되어 게시판을 이용할 수 있다. 콘텐츠를 이용하는 사용자이며 글을 게시하거나, 채팅 등의 활동을 할 수 있다.
    
    4. [] IA(Information Archtecture) 설계 (정보 설계 디자인) 
        1. []Depth 설계하기 (최대 깊이는 3개를 넘지 않도록 구성해본다-정말 필요시 초과 가능)
            - [] 1Depth(기능은 5개 정도로 고민중 예시 : 홈 / 취업(hrd) / 수업(학원) / 채팅 / 전체)
            - [] 2Depth(토스의 경우 대게 2Depth에서 종료됨)
        2. []형태 설정하기
        - [30%] 디자인 작성중.
        - 참고: [링크](https://tonicwaterpool.wordpress.com/2020/03/25/ia-%EC%99%80-flowchart-%ED%99%94%EB%A9%B4%ED%9D%90%EB%A6%84%EB%8F%84/)
        - 참고: [링크](https://brunch.co.kr/@66c669db056d4f7/15)
        - 정보구조도 디자인 참고: [링크](https://yozm.wishket.com/magazine/detail/1606/)
         

    4. [] 서비스 흐름(Service FlowChart Design)
        - 
1. []백엔드 구현(JAVA SpringBoot or Python? Django?) 
    1. [x]README.md 만들기
        - [x] 프로젝트 일정 구성하기 - workDown 방식으로 상세화 시킬 것 
        
2. []프론트 디자인
    1. []피그마 디자인
        - [x] 기본적인 예제 디자인 참고하기 [링크](https://www.next-t.co.kr/blog/%EC%9C%A0%EC%9A%A9%ED%95%9C%EC%9E%90%EB%A3%8C%EC%8B%A4-%EC%9B%B9%EC%82%AC%EC%9D%B4%ED%8A%B8%EB%B2%A4%EC%B9%98%EB%A7%88%ED%82%B9-%ED%95%B4%EC%99%B8%EC%9B%B9%EB%94%94%EC%9E%90%EC%9D%B8%EC%96%B4%EC%9B%8C%EB%93%9C-%EC%9C%A0%EB%AA%85%EC%82%AC%EC%9D%B4%ED%8A%B8)
        - []

3. []서버 구현 (Redis)
    1. []DB선택(Postgre?)
        - [] ERD 구성하기
        - [] 
    
### API 사용설명서(추후 추가 예정)
1. 

### 과제 진행시 유의사항

1. git-flow 전략을 사용하여 git을 관리한다.
    1. 참고사이트
        - [링크](https://techblog.woowahan.com/2553/)
        - [링크](https://velog.io/@kw2577/Git-branch-%EC%A0%84%EB%9E%B5)
        - [링크](https://inpa.tistory.com/entry/GIT-%E2%9A%A1%EF%B8%8F-github-flow-git-flow-%F0%9F%93%88-%EB%B8%8C%EB%9E%9C%EC%B9%98-%EC%A0%84%EB%9E%B5)
    2. 우선 이해한 내용 정리하면 git을 활용한 전략이 다양하며 그 중에서 이번 과제는 git-flow전략을 사용한다.
        1. gitflow에는 5가지의 branch가 존재한다
            - **master** : 기준이 되는 브랜치 - 제품 배포
            - **develop** : 개발이 진행되는 브랜치 - 개발자들은 작업이 완료된 코드를 이곳에 Merge한다
            - **feature** : 단위기능별 브랜치 - 단위기능이 완료되면 develop branch에 Merge한다
            - **release** : 품질검사 브랜치 - 배포되는 master branch에 push 전 QA가 진행되는 브랜치
            - **hotfix** : master branch가 배포된 이후 발견된 버그를 긴급 수정하기 위한 branch

        - master와 develop 기준으로 큰 맥락이 존재하며 나머지는 세부적 코드 개발/ 통합 / 테스트 / 긴급 수정 등을 진행한다.

2.  Java 코딩 컨벤션을 준수하며 프로젝트를 진행한다[링크](https://naver.github.io/hackday-conventions-java/)
    1. 파일 공통요건
        - 파일 인코딩: UTF-8 준수
        - 새줄 문자는 LF
        - 코드의 마지막은 새줄로 종료
    2. 이름(Naming)명명 방식
        - 식별자에는 영문/숫자/언더바만 허용
        - 가급적 발음만 쫒아가는 것이 아닌 단어의 의미를 통해 유추하도록 구성
        - 대문자를 통한 약어를 정의할 경우 명시할 것
        - **패키지 이름은 소문자로 구성한다**
        - **클래스/인터페이스 이름은 대문자 카멜표기법을 적용한다**
        - **클래스 이름은 명사형으로 표기한다**
        - **인터페이스 이름은 형용사형으로 표기한다**
        - **테스트 클래스는 Test로 종료한다**
        - **메서드 이름은 소문자 카멜표기법을 적용한다**
        - **메서드 이름은 동사/전치사로 시작한다**
        - 상수는 대문자와 언더바로 구성한다
        - 변수에 소문자 카멜표키법을 적용한다.
        - 변수에는 1글자 이름을 사용을 금지한다.
    3. 선언방식(클래스/필드/메서드/변수/import)
        - *** 각 파일은 1개의 탑레벨 클래스가 존재한다(Solid의 단일책임원칙과 동일) ***
        - import시에 *(와일드카드)사용은 Static일 경우에만 사용한다.
        - 제한자 선언 순서를 지킨다 (public - proteted - private - abstract - static - final)
        - 어노테이션 선언 이후에는 새줄을 사용한다
        - 한 줄에는 한 문장만
        - 하나의 선언문은 하나의 변수만
        - 배열은 타입 뒤에 선언한다
        - long타입은 숫자 뒤에 'L'을 대문자로 붙여서 가독성을 높인다.
        - 특수문자 전용 선언 방식을 활용한다(\n,\b,\f 등등)
    4. 들여쓰기 방식
        - 탭을 활용한다(스페이스와 구별)
        - 탭의 크기는 스페이스 4개와 동일하다.
        - 클래스,메서드,제어문 등의 코드 블럭이 생기면 들여쓰기를 활용한다.
    5. 중괄호 방식(클래스/메서드 선언 및 조건/반복문 등 코드 블럭을 감싸는 중괄호 방식)
        - 기본
            1. 줄의 마지에 시작 중괄호
            2. 시작 중괄호 이후 새줄 삽입
            3. 새줄 부터 블럭코드
            4. 블럭 종료 후 새줄 삽입
            5. 새줄 부터 닫는 중괄호
        - else, catch, finally, while는 닫는 중괄호와 같은 줄에 선언한다.
        - 내용이 없는 블럭을 선언할 경우 같은 줄에서 중괄호 닫는것을 허용한다.
        - 조건/반복문에 중괄호를 필수로 사용한다.

---
