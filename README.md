# Test Project for SpringBoot
- https://spring.io/guides/gs/spring-boot/

# 이 프로젝트는 
- VSCode를 사용하여 SpringBoot 프로젝트를 만들었다. 
- http://honeymon.io/tech/2021/01/06/use-vs-code-for-spring-boot.html
- https://spring.io/guides/gs/spring-boot/ 따라서 파일을 추가하였다.


# messages table 구조
```sql
CREATE TABLE messages (
    id      INT             AUTO_INCREMENT,
    text  VARCHAR(128)     NOT NULL DEFAULT '',
    create_date   DATETIME           NOT NULL DEFAULT CURRENT_TIMESTAMP,
    PRIMARY KEY (id)
);
```
