技术及工具
--------

|Catalog               |Official Site                |Source Version   |Specific Version Docs  |
|:---------------------|:----------------------------|:----------------|:----------------------|
|Build System          |[Gradle][bs-1]               |[2.12][bs-2]     |[User Guide][bs-3]<br>[Build Language Reference][bs-4]<br/>[javadoc][bs-5]<br/>[groovydoc][bs-6]|
|Cache                 |[ehcache][ce-o]              |core 2.6.9       |                       |
|                      |[redis][cr-o]                |[3.2.4][cr-s]    |[Documentation][cr-d]  |
|Common Utilities      |[Commons Lang][cu-cl-o]      |[3.4][cu-cl-s]   |[Online Documentation][cu-cl-d]|
|                      |[Joda-Time][cu-jt-o]         |[2.9.4][cu-jt-s] |Online Doc [quick][cu-jt-d1] & [full][cu-jt-d2]|
|Connection Pool       |HikariCP                     |[2.4.9][cp-h-s]  ||
|Continuous Integration|[TeamCity][ci-tc-o]          |[10.0.5][ci-tc-s]|[Online Documentation][ci-tc-d]|
|Data Access Layer     |[Spring Data JPA][sdj-1]     |[1.9.4][sdj-2]   |[Reference][sdj-3]     |
|Database              |[H2 Database][db-1]          |[1.3.176][db-2]  |[Documentation][db-3]<br>[javadoc][db-4]|
|[EAI][eai]            |[Spring Integration][si-o]   |[4.3.9][si-s]    |[Reference][si-d]      |
|Gradle Plugin         |[Gretty][gpg-1]              |[1.2.4][gpg-2]   |[Documentation][gpg-3] |
|JPA                   |[JSR 338][jpa-0]             |[2.1][jpa-1]     |[Specification][jpa-2] |
|Quality Tools         |[Checkstyle][qt-cs-o]        |[6.19][qt-cs-s]  |[Online Documentation][qt-cs-d]|
|                      |[Codecov][qt-cc-o]           |                 |[Online Documentation][qt-cc-d]|
|                      |[CodeNarc][qt-cn-o]          |[0.25.2][qt-cn-s]|                       |
|                      |[FindBugs][qt-fb-o]          |[3.0.1][qt-fb-s] |[Online Documentation][qt-fb-d]|
|                      |[JaCoCo][qt-jcc-o]           |[0.7.7][qt-jcc-s]|[Online Documentation][qt-jcc-d]|
|Servlet               |[JSR 315][s-1]               |[3.0.1][s-2]     |[Specification Final Release 2009][s-3] <br> [Specification Maintenance Release 2011][s-4] <br> [schema][s-5] <br> [javadoc][s-6] |
|Servlet Container     |[Tomcat][sc-1]               |[7.0.69][sc-2]   |[Documentation][sc-3]  |
|Spring                |[Spring Framework][s-sf-o]   |[4.3.0][s-sf-s]  |[Reference][s-sf-d]    |
|Test Frameworks       |[JUnit][tf-ju-o]             |[4.12][tf-ju-s]  |[javadoc][tf-ju-d]     |
|                      |[Spock Framework][tf-sf-o]   |[1.0][tf-sf-s]   |[Documentation][tf-sf-d1] <br> [javadoc][tf-sf-d2]|
|Workflow Platform     |[Activiti][wp-1]             |[5.22.0][wp-2]   |[Activiti Readme][wp-3]|
|Workflow Web Designer |[Activit Web Designer][wwd-1]|                 |                       |


[bs-1]: http://gradle.org/
[bs-2]: https://github.com/gradle/gradle/tree/REL_2.12
[bs-3]: projects/gradle/2.12/userguide/userguide_single.html
[bs-4]: projects/gradle/2.12/dsl/index.html
[bs-5]: projects/gradle/2.12/javadoc/index.html
[bs-6]: projects/gradle/2.12/groovydoc/index.html
[ce-o]: http://ehcache.org/
[ci-tc-o]: https://www.jetbrains.com/teamcity/
[ci-tc-s]: https://www.jetbrains.com/teamcity/download/
[ci-tc-d]: https://confluence.jetbrains.com/display/TCD10/TeamCity+Documentation
[cp-h-s]: https://github.com/brettwooldridge/HikariCP/tree/HikariCP-2.4.9
[cr-o]: http://redis.io/
[cr-s]: https://github.com/antirez/redis/tree/3.2.4
[cr-d]: https://github.com/antirez/redis-doc
[cu-cl-o]: http://commons.apache.org/proper/commons-lang/
[cu-cl-s]: https://github.com/apache/commons-lang/tree/LANG_3_4
[cu-cl-d]: http://commons.apache.org/proper/commons-lang/javadocs/api-3.4/index.html
[cu-jt-o]: http://www.joda.org/joda-time/
[cu-jt-s]: https://github.com/JodaOrg/joda-time/tree/v2.9.4
[cu-jt-d1]: http://www.joda.org/joda-time/quickstart.html
[cu-jt-d2]: http://www.joda.org/joda-time/userguide.html
[db-1]: http://h2database.com/html/main.html
[db-2]: https://github.com/h2database/h2database/tree/version-1.3/version-1.3.176/h2
[db-3]: projects/h2/1.3.176/index.html
[db-4]: projects/h2/1.3.176/javadoc/index.html
[eai]: https://en.wikipedia.org/wiki/Enterprise_application_integration
[gpg-1]: http://akhikhl.github.io/gretty-doc/Getting-started.html
[gpg-2]: https://github.com/akhikhl/gretty/tree/v1.2.4
[gpg-3]: projects/gretty/1.2.4/index.html
[jpa-0]: https://jcp.org/en/jsr/detail?id=338
[jpa-1]: https://jcp.org/aboutJava/communityprocess/final/jsr338/index.html
[jpa-2]: projects/JPA/2.1/JavaPersistence2.1.pdf
[qt-cc-o]: https://codecov.io/
[qt-cc-d]: https://codecov.io/docs
[qt-cn-o]: http://codenarc.sourceforge.net/
[qt-cn-s]: https://github.com/CodeNarc/CodeNarc/tree/v0.25.2
[qt-cs-o]: http://checkstyle.sourceforge.net/
[qt-cs-s]: https://github.com/checkstyle/checkstyle/tree/checkstyle-6.19
[qt-cs-d]: http://checkstyle.sourceforge.net/checks.html
[qt-fb-o]: http://findbugs.sourceforge.net/
[qt-fb-s]: https://github.com/findbugsproject/findbugs/tree/release-3.0.1
[qt-fb-d]: http://findbugs.sourceforge.net/manual/index.html
[qt-jcc-o]: http://eclemma.org/jacoco/
[qt-jcc-s]: https://github.com/jacoco/jacoco/tree/v0.7.7
[qt-jcc-d]: http://eclemma.org/jacoco/trunk/doc/
[s-1]: https://jcp.org/en/jsr/detail?id=315
[s-2]: projects/servlet/3.0/schema/javax.servlet.jar
[s-3]: projects/servlet/3.0/servlet-3_0-final-spec.pdf
[s-4]: projects/servlet/3.0/servlet-3_0-mrel-spec.pdf
[s-5]: projects/servlet/3.0/schema
[s-6]: projects/servlet/3.0/javadoc/index.html
[s-sf-o]: http://projects.spring.io/spring-framework/
[s-sf-s]: https://github.com/spring-projects/spring-framework/tree/v4.3.0.RELEASE
[s-sf-d]: projects/spring-framework/4.3.0/index.html
[sc-1]: http://tomcat.apache.org/
[sc-2]: http://archive.apache.org/dist/tomcat/tomcat-7/v7.0.69/src/
[sc-3]: projects/tomcat/7.0.69/index.html
[sdj-1]: http://www.springsource.org/spring-data
[sdj-2]: https://github.com/spring-projects/spring-data-jpa/tree/1.9.4.RELEASE
[sdj-3]: projects/spring-data-jpa/1.9.4/index.htm
[si-o]: http://projects.spring.io/spring-integration/
[si-s]: https://github.com/spring-projects/spring-integration/tree/v4.3.9.RELEASE
[si-d]: http://docs.spring.io/spring-integration/docs/4.3.9.RELEASE/reference/htmlsingle/
[tf-ju-o]: http://junit.org/junit4/
[tf-ju-s]: https://github.com/junit-team/junit/tree/r4.12
[tf-ju-d]: projects/junit/4.12/index.html
[tf-sf-o]: http://spockframework.org
[tf-sf-s]: https://github.com/spockframework/spock/tree/spock-1.0
[tf-sf-d1]: projects/spock/1.0/doc/index.html
[tf-sf-d2]: projects/spock/1.0/javadoc/index.html
[wp-1]: http://www.activiti.org/
[wp-2]: https://github.com/Activiti/Activiti/tree/activiti-5.22.0
[wp-3]: projects/activiti/5.22.0/readme.html
[wwd-1]: https://github.com/AlphaHinex/Activiti/tree/web-designer


辅助工具
------

|Catalog   |Tool                         |
|:---------|:----------------------------|
|UML & ERD |[StarUML](http://staruml.io/)|
|ICON      |[icomoon](https://icomoon.io/app/#/select)|


---


|Catalog|Version|
|:--|:--|
|JDK|oraclejdk7|
|Logging|[SLF4J 1.7.12](https://github.com/qos-ch/slf4j/tree/v_1.7.12)<br/>[Logback 1.1.3](https://github.com/qos-ch/logback)|
|Validator|Hibernate Validator 5.1.3.Final|
|JPA Provider|[Hibernate EntityManager 4.3.10.Final](https://github.com/hibernate/hibernate-orm/tree/4.3.10.Final)|
|任务调度|quartz 2.2.1|
|通用工具|guava 18.0|
|编码及加密|[common-codec 1.10](https://github.com/apache/commons-codec/tree/1.10)<br/>bounce-casle|
|xml|dom4j|
|JSON|[jackson-databind 2.3.6](https://github.com/FasterXML/jackson-databind/tree/jackson-databind-2.6.3)|
|消息队列||
|license||
