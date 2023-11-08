```mermaid
sequenceDiagram
    JavaApp->>JPA: Java 객체(DAO)
    JPA->>JDBC: JDBC API
    JDBC->>DBMS: SQL
    DBMS-->>JDBC: DB
    JDBC-->>JPA: API return
    JPA-->>JavaApp: 객체 return

```
SBB _SpringBoot Board_
-----------------------------
-----------------------------
### 스프링부트 게시판 입니다.
스프링부트 게시판 입니다.