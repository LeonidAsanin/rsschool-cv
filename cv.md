# Leonid Asanin
![photo](photo.jpg "Фотография")
# Contact info
+ Phone: +7-917-168-68-65
+ E-mail: l.asanin@mail.ru
+ GitHub: https://github.com/LeonidAsanin
# About me
I am a professional software developer who eager to learn more and more technologies, practice them, and solve current business problems. My main strength is an ability to communicate with people, understand them and convey information clearly.
# Skills
+ JavaScript, HTML, CSS
+ Java, Spring MVC, Spring Security, Spring Data, CUBA platform/JMIX, Liquibase, JUnit, RabbitMQ, Apache Kafka
+ SQL, PostgreSQL, MySQL
+ Maven, Gradle, Git, Docker
# Experience
+ **IT-Service, Fullstack Developer** (2022, June - current)
  - Pipeline Integrity Management System (Java, CUBA platform, JavaScript, PostgreSQL, Gradle)
  - Sigma ERP (JMIX, Java, Spring, JUnit, PostgreSQL, Liquibase, Gradle)
+ **AvtoVAZ, Design Engineer** (2020, October - 2022, June)
# Code example
LeetCode, Longest Common Prefix problem:

```javascript
/**
 * @param {string[]} strs
 * @return {string}
 */
let longestCommonPrefix = function(strs) {
    let prefix = '';

    for (let index = 0; index < strs[0].length; index++) {
        if (strs.some(string => string[index] !== strs[0][index])) {
            break;
        } else {
            prefix += strs[0][index];
        }
    }
    
    return prefix;
};
```
# Education
+ Samara University : Informatics, Mathematics and Electronics Institute, Bachelor (2016-2020)
# Languages
+ Russian (C2, Native)
+ English (B1, Intermediate)
