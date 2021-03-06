# CS Interview - Database

- [데이터베이스를 사용하는 이유가 뭔가요?](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/1.%20Why%20use%20database.md)
- [데이터베이스의 성능이란 무엇인가요?](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/2.%20Database%20performance.md)
- [데이터 모델에 대해서 설명해주세요.](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/3.%20Data%20model.md)
- [Index](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/4.%20Index.md)
  - Index 란 무엇인가    
  - Primary index vs Secondary index
  - Index 의 성능과 고려해야할 사항
  - 인덱스 Scan 방식은 무엇이 있나요?
  - 인덱스 설계시 NULL값은 고려되야 할까요?
- [Index 의 자료구조는 크게 Hash 인덱스와 B+Tree 인덱스가 있습니다. 이것은 무엇일까요?](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/5.%20Index%20Structure.md)
- [정규화](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/6.%20Normalization.md)
  - 정규화란 무엇인가
  - 정규화의 종류
  - 정규화의 장단점
- [트랜잭션(Transaction)이란 무엇인가?](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/7.%20Transaction.md)
  - 트랜잭션의 특성
  - 트랜잭션과 Lock
  - 트랜잭션의 상태
  - DBMS 는 어떻게 트랜잭션을 관리할까?
- [트랜잭션 격리 수준(Transaction Isolation Level)](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/8.%20Transaction%20Level.md)
  - 트랜잭션을 사용할 때 주의할 점
- [NoSQL](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/9.%20NoSQL.md)
  - NoSQL vs RDBMS  
  - 저장방식에 따른 분류
    - Key-Value Model
    - Document Model
    - Column Model
    - Graph Model
  - 대표적으로 MongoDB가 있는데, 다른 NoSQL과 다른 점이 뭘까요?
  - [CAP 이론](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/10.%20cap.md)
    - 일관성
    - 가용성
    - 네트워크 분할 허용성
- [Redis](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/11.%20Redis.md)
  - Redis에 장애가 발생할 경우 데이터 복구 방법
  - [Redis와 비슷한 기술](https://github.com/cow-coding/Keep-going-tech-interview/blob/main/Computer%20Science/Database/12.%20Broker.md)
    - Kafka
    - RabbitMQ
- 효과적인 쿼리 저장
- 옵티마이저(Optimizer)란
- Replication
- 파티셔닝(Partitioning)
- 샤딩(Sharding)
- Key 종류
- CRUD 
- SQL Join
- SQL injection
- Anomaly
  - 종류
  - 설명
  - 발생 예시
- Statement와 PrepareStatement
- 객체 관계 매핑(Object-relational mapping, ORM)이란
- java JDBC
- PostgreSQL의 장점은 무엇일까요?
  - postgreSQL vs Elastic Search
- Nested Loop 조인은 무엇일까요?
- Windows 함수는 무엇이고 어떻게 작성할까요?
- KNN 알고리즘을 쿼리로 구현할 수 있을까요?
- MySQL에서 대량의 데이터(500만개 이상)를 Insert해야하는 경우엔 어떻게 해야할까요?
- RDB의 char와 varchar의 차이는 무엇일까요?
- 구글의 BigQuery, AWS의 Redshift는 기존 RDB와 무슨 차이가 있을까요? 왜 빠를까요?
- 쿼리의 성능을 확인하기 위해 어떤 쿼리문을 작성해야 할까요?
- MySQL이 요새 느리다는 신고가 들어왔습니다. 첫번째로 무엇을 확인하시고 조정하시겠나요?
- 동작하는 MySQL에 Alter table을 하면 안되는 이유를 설명해주세요. 그리고 대안을 설명해주세요
- 빡세게 동작하고 있는 MySQL을 백업뜨기 위해서는 어떤 방법이 필요할까요?