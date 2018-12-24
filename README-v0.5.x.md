技术及工具
--------

|Catalog               |Official Site                |Source Version      |Specific Version Docs  |
|:---------------------|:----------------------------|:----------------   |:----------------------|
|Build System          |[Gradle][bs-1]               |[4.10.2][bs-2]     |[User Guide][bs-3]|
|Cache                 |[ehcache][ce-o]              |core 2.6.9          |                       |
|                      |[redis][cr-o]                |[2.3.2][cr-s]      |[Documentation][cr-d]  |
|Common Utilities      |[Commons Lang][cu-cl-o]      |[3.4][cu-cl-s]    |[Online Documentation][cu-cl-d]|
|Connection Pool       |[Druid][cp-d-o]              |[1.1.10][cp-d-s]  |[Configuration Properties][cp-d-cp]|
|Continuous Integration|[TeamCity][ci-tc-o]          |[10.0.5][ci-tc-s] |[Online Documentation][ci-tc-d]|
|Data Access Layer     |[Spring Data JPA][sdj-1]     |[1.9.4][sdj-2]    |[Reference][sdj-3]|
|Database              |[H2 Database][db-1]          |[1.4.197][db-2]   |[Documentation][db-3]|
|                      |[Liquibase][db-lb-o]         |[3.6.1][db-lb-s]  |[Documentation][db-lb-d]|
|JPA                   |[JSR 338][jpa-0]             |[2.1][jpa-1]      |[Specification][jpa-2] |
|JPA Provider          |[Hibernate EntityManager][jpa-he-o]|[4.3.10.Final][jpa-he-s]|[Documentation][jpa-he-d]|
|Quality Tools         |[Checkstyle][qt-cs-o]        |[8.14][qt-cs-s]  |[Online Documentation][qt-cs-d]|
|                      |[Codecov][qt-cc-o]           |                  |[Online Documentation][qt-cc-d]|
|                      |[CodeNarc][qt-cn-o]          |[1.2.1][qt-cn-s] |                       |
|                      |[FindBugs][qt-fb-o]          |[3.0.1][qt-fb-s] |[Online Documentation][qt-fb-d]|
|                      |[JaCoCo][qt-jcc-o]           |[0.8.2][qt-jcc-s]|[Online Documentation][qt-jcc-d]|
|                      |[P3C_PMD][qt-pmd-o]          |[1.3.6][qt-pmd-s]|[Online Documentation][qt-pmd-d]|
|Servlet               |[JSR 315][s-1]               |[3.0.1][s-2]      |[Specification Final Release 2009][s-3] <br> [Specification Maintenance Release 2011][s-4] <br> [schema][s-5] <br> [javadoc][s-6] |
|Servlet Container     |[Tomcat][sc-1]               |[7.0.69][sc-2]   |[Documentation][sc-3]  |
|Spring Boot           |[Spring Boot][s-sb-o]        |[2.0.6][s-sb-s]  |[Reference][s-sb-d]    |
|                      |[Spring Boot Gradle Plugin v2.0.6][sbgp]|          |                       |
|Spring                |[Spring Framework][s-sf-o]   |[5.1.2][s-sf-s]  |[Reference][s-sf-d]    |
|Swagger               |[Spring Fox][s-s-o]          |[3.0.0-SNAPSHOT][s-s-s]   |[Reference][s-s-d]    |
|Test Frameworks       |[JUnit][tf-ju-o]             |[4.12][tf-ju-s]  |[javadoc][tf-ju-d]     |
|                      |[Spock Framework][tf-sf-o]   |[1.0][tf-sf-s]   |[Documentation][tf-sf-d1] <br> [javadoc][tf-sf-d2]|
|Workflow Platform     |[Flowable][wp-1]             |[6.4.0][wp-2]    |[FlowableDocs][wp-3]|
|Workflow Web Designer |[Activit Web Designer][wwd-1]|                  |                       |


[bs-1]: http://gradle.org/
[bs-2]: https://github.com/gradle/gradle/tree/v4.10.2
[bs-3]: https://docs.gradle.org/4.10.2/userguide/userguide.html
[bs-4]: projects/gradle/2.12/dsl/index.html
[bs-5]: projects/gradle/2.12/javadoc/index.html
[bs-6]: projects/gradle/2.12/groovydoc/index.html
[ce-o]: http://ehcache.org/
[ci-tc-o]: https://www.jetbrains.com/teamcity/
[ci-tc-s]: https://www.jetbrains.com/teamcity/download/
[ci-tc-d]: https://confluence.jetbrains.com/display/TCD10/TeamCity+Documentation
[cp-d-o]: https://github.com/alibaba/druid
[cp-d-s]: https://github.com/alibaba/druid/tree/1.1.11
[cp-d-cp]: https://github.com/alibaba/druid/wiki/FAQ  
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
[db-2]: https://github.com/h2database/h2database/tree/version-1.4.197/h2
[db-3]: http://h2database.com/html/main.html
[db-lb-o]: http://www.liquibase.org/
[db-lb-s]: https://github.com/liquibase/liquibase/tree/liquibase-parent-3.6.1
[db-lb-d]: http://www.liquibase.org/documentation/index.html
[eai]: https://en.wikipedia.org/wiki/Enterprise_application_integration
[gpg-1]: http://akhikhl.github.io/gretty-doc/Getting-started.html
[gpg-2]: https://github.com/akhikhl/gretty/tree/v1.2.4
[gpg-3]: projects/gretty/1.2.4/index.html
[jpa-0]: https://jcp.org/en/jsr/detail?id=338
[jpa-1]: https://jcp.org/aboutJava/communityprocess/final/jsr338/index.html
[jpa-2]: projects/JPA/2.1/JavaPersistence2.1.pdf
[jpa-he-o]: http://hibernate.org/orm/
[jpa-he-s]: https://github.com/hibernate/hibernate-orm/tree/4.3.10.Final
[jpa-he-d]: http://hibernate.org/orm/documentation/4.3/
[qt-cc-o]: https://codecov.io/
[qt-cc-d]: https://codecov.io/docs
[qt-cn-o]: http://codenarc.sourceforge.net/
[qt-cn-s]: https://github.com/CodeNarc/CodeNarc/tree/v1.2.1
[qt-cs-o]: http://checkstyle.sourceforge.net/
[qt-cs-s]: https://github.com/checkstyle/checkstyle/tree/checkstyle-8.14
[qt-cs-d]: http://checkstyle.sourceforge.net/checks.html
[qt-fb-o]: http://findbugs.sourceforge.net/
[qt-fb-s]: https://github.com/findbugsproject/findbugs/tree/release-3.0.1
[qt-fb-d]: http://findbugs.sourceforge.net/manual/index.html
[qt-jcc-o]: http://eclemma.org/jacoco/
[qt-jcc-s]: https://github.com/jacoco/jacoco/tree/v0.8.2
[qt-jcc-d]: http://eclemma.org/jacoco/trunk/doc/
[qt-pmd-o]: https://github.com/alibaba/p3c
[qt-pmd-s]: https://github.com/alibaba/p3c/tree/p3c-pmd-1.3.6
[qt-pmd-d]: https://github.com/alibaba/p3c/blob/master/%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4Java%E5%BC%80%E5%8F%91%E6%89%8B%E5%86%8C%EF%BC%88%E8%AF%A6%E5%B0%BD%E7%89%88%EF%BC%89.pdf
[s-1]: https://jcp.org/en/jsr/detail?id=315
[s-2]: projects/servlet/3.0/schema/javax.servlet.jar
[s-3]: projects/servlet/3.0/servlet-3_0-final-spec.pdf
[s-4]: projects/servlet/3.0/servlet-3_0-mrel-spec.pdf
[s-5]: projects/servlet/3.0/schema
[s-6]: projects/servlet/3.0/javadoc/index.html
[s-sb-o]: https://spring.io/projects/spring-boot
[s-sf-o]: http://projects.spring.io/spring-framework/
[s-sb-s]: https://github.com/spring-projects/spring-boot/tree/v2.0.6.RELEASE
[s-sf-s]: https://github.com/spring-projects/spring-framework/tree/v5.1.2.RELEASE
[s-sb-d]: https://docs.spring.io/spring-boot/docs/2.0.6.RELEASE/reference/htmlsingle/
[s-sf-d]: https://docs.spring.io/spring/docs/5.1.2.RELEASE/spring-framework-reference/
[sbgp]: https://docs.spring.io/spring-boot/docs/2.0.6.RELEASE/gradle-plugin/reference/html/
[sc-1]: http://tomcat.apache.org/
[sc-2]: http://archive.apache.org/dist/tomcat/tomcat-7/v7.0.69/src/
[sc-3]: https://tomcat.apache.org/tomcat-7.0-doc/index.html
[sdj-1]: https://spring.io/projects/spring-data-jpa
[sdj-2]: https://github.com/spring-projects/spring-data-jpa/tree/1.9.4.RELEASE
[sdj-3]: https://docs.spring.io/spring-data/jpa/docs/1.9.4.RELEASE/reference/html/
[s-s-o]: http://springfox.github.io/springfox/
[s-s-s]: https://github.com/springfox/springfox
[s-s-d]:  http://springfox.github.io/springfox/docs/snapshot/
[tf-ju-o]: http://junit.org/junit4/
[tf-ju-s]: https://github.com/junit-team/junit/tree/r4.12
[tf-ju-d]: projects/junit/4.12/index.html
[tf-sf-o]: http://spockframework.org
[tf-sf-s]: https://github.com/spockframework/spock/tree/spock-1.0
[tf-sf-d1]: projects/spock/1.0/doc/index.html
[tf-sf-d2]: projects/spock/1.0/javadoc/index.html
[wp-1]: https://www.flowable.org/
[wp-2]: https://github.com/flowable/flowable-engine/tree/flowable-6.4.0
[wp-3]: https://www.flowable.org/docs/userguide/index.html#_getting_started
[wwd-1]: https://github.com/AlphaHinex/Activiti/tree/web-designer
