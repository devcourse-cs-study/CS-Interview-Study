# CS-Interview-Study
## 스터디 소개 
- ### 멤버

<table>
  <tr>
    <td>
        <a href="https://github.com/suy2on">
            <img src="https://avatars.githubusercontent.com/u/62363580?v=4" width="100px" />
        </a>
    </td>
    <td>
        <a href="https://github.com/Nnagman">
            <img src="https://avatars.githubusercontent.com/u/16336810?v=4" width="100px" />
        </a>
    </td>
    <td>
        <a href="https://github.com/pppp0722">
            <img src="https://avatars.githubusercontent.com/u/60428537?v=4" width="100px" />
        </a>
    </td>
    <td>
        <a href="https://github.com/ChoiYeonho0903">
            <img src="https://avatars.githubusercontent.com/u/76257508?v=4" width="100px" />
        </a>
    </td>
    <td>
        <a href="https://github.com/su-pernova">
            <img src="https://avatars.githubusercontent.com/u/48689213?v=4" width="100px" />
        </a>
    </td>
  </tr>
  <tr>
    <td><b>이수연</b></td>
    <td><b>이창호</b></td>
    <td><b>이일환</b></td>
    <td><b>최연호</b></td>
    <td><b>김수미</b></td>
  </tr>
</table>


- ### 스터디 주제 순서
```
OS → 네트워크 → DB → JAVA → 자료구조/알고리즘 → Spring
```
- ### 스터디 시간
```
화 : 20:00 ~ 22:00
토 : 14:30 ~ 16:30
```
- ### 스터디 진행방식
```
정해진 주제에 대해 공부하고 예상질문을 만들어옵니다.
스터디 시작 전 면접자를 골라 해당 주제에 대해 40분동안 일대다 면접을 진행합니다.
20분동안 피드백을 주고받습니다. 
```
## 스터디 기록

<details>
<summary><b>⚙️ 운영체제</b></summary>
<div markdown="1">
<br>

- 운영체제 소개
  - 운영체제 필요성
  - 운영체제 정의
  - 운영체제 역할
- 운영체제 구조
  - 커널
  - 시스템 호출
- 프로세스
  - 프로세스 개념
  - 프로세스 상태
  - 프로세스 제어 블록
  - 프로세스 문맥 교환
- 스레드
  - 스레드 개념
  - 멀티스레드의 구조
  - 멀티스레드의 장단점
  - 멀티 프로세스 VS 멀티 스레드
- CPU 스케줄링
  - 장기 스케줄링
  - 중기 스케줄링
  - 단기 스케줄링
- 스케줄링 알고리즘
  - FCFS
  - SJF
  - Round Robin
  - SRT
  - Priority scheduling
  - Multilevel Queue
  - Multilevel Feedback Queue
- 인터럽트
  - 인터럽트 개념
  - 동기적 인터럽트, 비동기적 인터럽트
  - 인터럽트 처리 과정
  - 인터럽트와 이중 모드
- 프로세스 동기화
  - 공유자원, 경쟁상태, 임계구역
  - 피터슨 알고리즘
  - 뮤텍스
  - 세마포어
  - 모니터
- 교착 상태(Deadlock)
  - 교착 상태 정의
  - 교착 상태 조건
  - 교착 상태 해결 방법
  - 식사하는 철학자 문제
- 메모리 관리
  - 메모리 관리 필요성
  - 고정 분할 방식
  - 가변 분할 방식
- 가상 메모리
  - 가상 메모리 정의
  - 가상 메모리 필요성
  - 페이징 기법
  - 세그먼테이션 기법
- 가상 메모리 관리
  - 요구 페이징
- 페이지 교체 알고리즘
  - FIFO
  - OPT
  - LRU
</div>
</details>

<details>
<summary><b>🌏 네트워크</b></summary>
<div markdown="1">
<br>

- OSI 7 계층
  - OSI 7 계층 개념
  - 웹 서버(Apache, Nginx) 동작 레이어
- TCP와 UDP
  - TCP와 UDP 개념
  - TCP/IP 통신
- HTTP 통신
  - HTTP 통신 개념
  - HTTP vs HTTPS
  - HTTP method (POST, GET, PUT 등)
  - TLS/SSL HandShake
- REST API, RESTful
- 로드 밸런싱(Load Balancing)
- 라우팅 알고리즘
- 블로킹/논블로킹 & 동기/비동기
- 도메인 네임 서버 (DNS)
- 교차 출처 리소스 공유 (CORS)
</div>
</details>

<details>
<summary><b>📚 데이터베이스</b></summary>
<div markdown="1">
<br>

- 트랜잭션
  - 트랜잭션 개념
  - ACID
  - 트랜잭션 격리 수준(Transaction Isolation Levels)
- 데이터베이스 정규화
  - 정규화 vs 역정규화
  - 이상 현상 (Anomaly)
- JOIN
  - JOIN 개념
  - JOIN 의 종류
- KEY
  - KEY 개념
  - KEY 종류
- DBMS
  - RDBMS vs NOSQL
  - 인덱스를 사용하는 이유 및 장단점
  - Redis 개념
  - Elastic Search 개념 (Message Queue)
</div>
</details>


<details>
<summary><b>☕️ JAVA</b></summary>
<div markdown="1">
<br>

- JVM
  - JVM 구조
  - Java 실행 방식
- GC
  - GC 가 무엇인지
  - 필요한 이유
  - 동작 방식
- 제네릭
- 어노테이션
- 오버라이딩 vs 오버로딩
- 접근 제어자
- 클래스 vs 인터페이스 vs 추상클래스
- 자바의 원시타입 (종류와 크기)
- 객체지향
  - 객체지향 개념
  - SOLID (객체지향 5대원칙)
  - 디자인 패턴의 종류
- 강한 결합 vs 느슨한 결합
- 직렬화 vs 역직렬화
- Call by value vs Call by reference
- Mutable 객체 vs Immutable 객체
- 오토 박싱 vs 오토 언박싱
</div>
</details>



<details>
<summary><b>🧠 자료구조/알고리즘</b></summary>
<div markdown="1">
<br>

- Stack vs Queue
- Hash Function & HashTable
- Heap & Priority Queue
- Tree, Binary Tree, BST, AVL Tree
- DFS vs BFS
</div>
</details>

<details>
<summary><b>🌿 Spring</b></summary>
<div markdown="1">
<br>

- Spring DI/IoC
  - 동작 방식
  - 종류
  - IoC 컨테이너
- Spring Bean
  - 스프링 Bean 생성 과정
  - 스프링 Bean의 Scope
- Autowiring
- Spring Web MVC
  - 개념
  - Dispatcher Servlet
- Spring 에서 CORS 에러를 해결하기 위한 방법
- JPA
  - JPA 영속성 컨텍스트의 이점
  - N + 1 문제 (원인, 해결 방법)
</div>
</details>
