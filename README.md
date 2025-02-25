## sudeep@sudeep-Inspiron-3476:~/Documents/study/java$ /usr/bin/env /usr/lib/jvm/java-17-openjdk-amd64/bin/java @/tmp/cp_9l2k7qlbccg05hcbcmmrx4kuy.argfile com.org.app.prac.PracApplication

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T20:55:19.389+09:00 INFO 8304 --- [prac] [ main] com.org.app.prac.PracApplication : Starting PracApplication using Java 17.0.14 with PID 8304 (/home/sudeep/Documents/study/java/prac/target/classes started by sudeep in /home/sudeep/Documents/study/java)

## 2025-02-25T20:55:19.393+09:00 INFO 8304 --- [prac] [ main] com.org.app.prac.PracApplication : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T20:55:20.351+09:00 INFO 8304 --- [prac] [ main] com.org.app.prac.PracApplication : Started PracApplication in 1.61 seconds (process running for 2.192)

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java$ mvn package

## [INFO] Scanning for projects...

## [INFO] ------------------------------------------------------------------------

## [INFO] BUILD FAILURE

## [INFO] ------------------------------------------------------------------------

## [INFO] Total time: 0.102 s

## [INFO] Finished at: 2025-02-25T21:19:26+09:00

## [INFO] ------------------------------------------------------------------------

## [ERROR] The goal you specified requires a project to execute but there is no POM in this directory (/home/sudeep/Documents/study/java). Please verify you invoked Maven from the correct directory. -> [Help 1]

## [ERROR]

## [ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.

## [ERROR] Re-run Maven using the -X switch to enable full debug logging.

## [ERROR]

## [ERROR] For more information about the errors and possible solutions, please read the following articles:

## [ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MissingProjectException

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java$ ls

## prac

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java$ cd prac/

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ mvn package

## [INFO] Scanning for projects...

## [INFO]

## [INFO] --------------------------< com.org.app:prac >--------------------------

## [INFO] Building prac 0.0.1-SNAPSHOT

## [INFO] --------------------------------[ jar ]---------------------------------

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/3.5.2/maven-surefire-plugin-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-surefire-plugin/3.5.2/maven-surefire-plugin-3.5.2.pom (5.7 kB at 15 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire/3.5.2/surefire-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire/3.5.2/surefire-3.5.2.pom (20 kB at 310 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/43/maven-parent-43.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/43/maven-parent-43.pom (50 kB at 719 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.4.2/maven-jar-plugin-3.4.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-jar-plugin/3.4.2/maven-jar-plugin-3.4.2.pom (7.7 kB at 256 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/42/maven-plugins-42.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/42/maven-plugins-42.pom (7.7 kB at 220 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/42/maven-parent-42.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/42/maven-parent-42.pom (50 kB at 1.1 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/32/apache-32.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/32/apache-32.pom (24 kB at 756 kB/s)

## [INFO]

## [INFO] --- maven-resources-plugin:3.3.1:resources (default-resources) @ prac ---

## [INFO] Copying 1 resource from src/main/resources to target/classes

## [INFO] Copying 0 resource from src/main/resources to target/classes

## [INFO]

## [INFO] --- maven-compiler-plugin:3.13.0:compile (default-compile) @ prac ---

## [INFO] Recompiling the module because of added or removed source files.

## [INFO] Compiling 1 source file with javac [debug parameters release 17] to target/classes

## [INFO]

## [INFO] --- maven-resources-plugin:3.3.1:testResources (default-testResources) @ prac ---

## [INFO] skip non existing resourceDirectory /home/sudeep/Documents/study/java/prac/src/test/resources

## [INFO]

## [INFO] --- maven-compiler-plugin:3.13.0:testCompile (default-testCompile) @ prac ---

## [INFO] Recompiling the module because of changed dependency.

## [INFO] Compiling 1 source file with javac [debug parameters release 17] to target/test-classes

## [INFO]

## [INFO] --- maven-surefire-plugin:3.5.2:test (default-test) @ prac ---

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.2/surefire-api-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.2/surefire-api-3.5.2.pom (3.5 kB at 33 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.2/surefire-logger-api-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.2/surefire-logger-api-3.5.2.pom (3.3 kB at 58 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.2/surefire-shared-utils-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.2/surefire-shared-utils-3.5.2.pom (4.7 kB at 53 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.2/surefire-extensions-api-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.2/surefire-extensions-api-3.5.2.pom (3.5 kB at 95 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.2/maven-surefire-common-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.2/maven-surefire-common-3.5.2.pom (7.8 kB at 182 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.2/surefire-booter-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.2/surefire-booter-3.5.2.pom (4.8 kB at 121 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.2/surefire-extensions-spi-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.2/surefire-extensions-spi-3.5.2.pom (1.8 kB at 57 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.pom (2.8 kB at 82 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver/1.4.1/maven-resolver-1.4.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver/1.4.1/maven-resolver-1.4.1.pom (18 kB at 433 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/33/maven-parent-33.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/33/maven-parent-33.pom (44 kB at 939 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/21/apache-21.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/21/apache-21.pom (17 kB at 417 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.pom (2.6 kB at 71 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.pom (5.4 kB at 103 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/42/maven-shared-components-42.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/42/maven-shared-components-42.pom (3.8 kB at 14 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/1.3.0/plexus-java-1.3.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/1.3.0/plexus-java-1.3.0.pom (14 kB at 261 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.pom (2.4 kB at 88 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.1.0/qdox-2.1.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.1.0/qdox-2.1.0.pom (18 kB at 533 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.2/surefire-api-3.5.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.2/surefire-logger-api-3.5.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.2/surefire-shared-utils-3.5.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.2/surefire-extensions-api-3.5.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.2/maven-surefire-common-3.5.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-logger-api/3.5.2/surefire-logger-api-3.5.2.jar (14 kB at 129 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.2/surefire-booter-3.5.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-api/3.5.2/surefire-api-3.5.2.jar (171 kB at 1.0 MB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-api/3.5.2/surefire-extensions-api-3.5.2.jar (26 kB at 152 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.2/surefire-extensions-spi-3.5.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-extensions-spi/3.5.2/surefire-extensions-spi-3.5.2.jar (8.2 kB at 35 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-booter/3.5.2/surefire-booter-3.5.2.jar (118 kB at 338 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-util/1.4.1/maven-resolver-util-1.4.1.jar (168 kB at 401 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/1.3.0/plexus-java-1.3.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.4.0/maven-common-artifact-filters-3.4.0.jar (58 kB at 138 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/maven-surefire-common/3.5.2/maven-surefire-common-3.5.2.jar (311 kB at 724 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.jar

## Downloading from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.1.0/qdox-2.1.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/resolver/maven-resolver-api/1.4.1/maven-resolver-api-1.4.1.jar (149 kB at 339 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.1/plexus-utils-1.1.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-java/1.3.0/plexus-java-1.3.0.jar (57 kB at 108 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.7/asm-9.7.jar (125 kB at 220 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/1.1/plexus-utils-1.1.jar (169 kB at 263 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/com/thoughtworks/qdox/qdox/2.1.0/qdox-2.1.0.jar (348 kB at 535 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-shared-utils/3.5.2/surefire-shared-utils-3.5.2.jar (2.8 MB at 3.8 MB/s)

## [INFO] Using auto detected provider org.apache.maven.surefire.junitplatform.JUnitPlatformProvider

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/3.5.2/surefire-junit-platform-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/3.5.2/surefire-junit-platform-3.5.2.pom (5.7 kB at 119 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/3.5.2/surefire-providers-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-providers/3.5.2/surefire-providers-3.5.2.pom (2.6 kB at 75 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/common-java5/3.5.2/common-java5-3.5.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/common-java5/3.5.2/common-java5-3.5.2.pom (2.8 kB at 92 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.9.3/junit-platform-engine-1.9.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.9.3/junit-platform-engine-1.9.3.pom (3.2 kB at 107 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.pom (1.7 kB at 51 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.9.3/junit-platform-commons-1.9.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.9.3/junit-platform-commons-1.9.3.pom (2.8 kB at 91 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.9.3/junit-platform-launcher-1.9.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.9.3/junit-platform-launcher-1.9.3.pom (3.0 kB at 38 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/3.5.2/surefire-junit-platform-3.5.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.9.3/junit-platform-commons-1.9.3.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.9.3/junit-platform-engine-1.9.3.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/common-java5/3.5.2/common-java5-3.5.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/opentest4j/opentest4j/1.2.0/opentest4j-1.2.0.jar (7.7 kB at 120 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.9.3/junit-platform-launcher-1.9.3.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/surefire-junit-platform/3.5.2/surefire-junit-platform-3.5.2.jar (27 kB at 403 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/surefire/common-java5/3.5.2/common-java5-3.5.2.jar (18 kB at 231 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-engine/1.9.3/junit-platform-engine-1.9.3.jar (189 kB at 1.6 MB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-commons/1.9.3/junit-platform-commons-1.9.3.jar (103 kB at 798 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.9.3/junit-platform-launcher-1.9.3.jar (169 kB at 1.2 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.11.4/junit-platform-launcher-1.11.4.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.11.4/junit-platform-launcher-1.11.4.pom (3.0 kB at 112 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.11.4/junit-platform-launcher-1.11.4.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/platform/junit-platform-launcher/1.11.4/junit-platform-launcher-1.11.4.jar (189 kB at 3.0 MB/s)

## [INFO]

## [INFO] -------------------------------------------------------

## [INFO] T E S T S

## [INFO] -------------------------------------------------------

## [INFO] Running com.org.app.prac.PracApplicationTests

## 21:19:56.148 [main] INFO org.springframework.test.context.support.AnnotationConfigContextLoaderUtils -- Could not detect default configuration classes for test class [com.org.app.prac.PracApplicationTests]: PracApplicationTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.

## 21:19:56.333 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper -- Found @SpringBootConfiguration com.org.app.prac.PracApplication for test class com.org.app.prac.PracApplicationTests

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T21:19:56.915+09:00 INFO 21155 --- [prac] [ main] com.org.app.prac.PracApplicationTests : Starting PracApplicationTests using Java 17.0.14 with PID 21155 (started by sudeep in /home/sudeep/Documents/study/java/prac)

## 2025-02-25T21:19:56.918+09:00 INFO 21155 --- [prac] [ main] com.org.app.prac.PracApplicationTests : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T21:19:57.532+09:00 INFO 21155 --- [prac] [ main] com.org.app.prac.PracApplicationTests : Started PracApplicationTests in 1.007 seconds (process running for 2.502)

## OpenJDK 64-Bit Server VM warning: Sharing is only supported for boot loader classes because bootstrap classpath has been appended

## [INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 2.647 s -- in com.org.app.prac.PracApplicationTests

## [INFO]

## [INFO] Results:

## [INFO]

## [INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

## [INFO]

## [INFO]

## [INFO] --- maven-jar-plugin:3.4.2:jar (default-jar) @ prac ---

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.1.0/file-management-3.1.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.1.0/file-management-3.1.0.pom (4.5 kB at 102 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/36/maven-shared-components-36.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/36/maven-shared-components-36.pom (4.9 kB at 122 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/36/maven-parent-36.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/36/maven-parent-36.pom (45 kB at 1.3 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/26/apache-26.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/26/apache-26.pom (21 kB at 622 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.pom (7.8 kB at 212 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.pom (20 kB at 491 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/69/commons-parent-69.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/69/commons-parent-69.pom (77 kB at 1.2 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.2/maven-archiver-3.6.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.2/maven-archiver-3.6.2.pom (4.4 kB at 104 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/41/maven-shared-components-41.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/41/maven-shared-components-41.pom (3.2 kB at 68 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.9.2/plexus-archiver-4.9.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.9.2/plexus-archiver-4.9.2.pom (6.0 kB at 107 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.4.2/plexus-io-3.4.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.4.2/plexus-io-3.4.2.pom (3.9 kB at 125 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/16/plexus-16.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/16/plexus-16.pom (28 kB at 892 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.10.1/junit-bom-5.10.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.10.1/junit-bom-5.10.1.pom (5.6 kB at 202 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.26.1/commons-compress-1.26.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.26.1/commons-compress-1.26.1.pom (22 kB at 639 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/66/commons-parent-66.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/66/commons-parent-66.pom (77 kB at 2.2 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.16.1/commons-codec-1.16.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.16.1/commons-codec-1.16.1.pom (16 kB at 461 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.14.0/commons-lang3-3.14.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.14.0/commons-lang3-3.14.0.pom (31 kB at 835 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/64/commons-parent-64.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/64/commons-parent-64.pom (78 kB at 1.4 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/30/apache-30.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/30/apache-30.pom (23 kB at 750 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.pom (15 kB at 519 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.9/xz-1.9.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.9/xz-1.9.pom (2.0 kB at 82 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.5-11/zstd-jni-1.5.5-11.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.5-11/zstd-jni-1.5.5-11.pom (2.0 kB at 54 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.27/plexus-interpolation-1.27.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.27/plexus-interpolation-1.27.pom (3.0 kB at 116 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.1.0/file-management-3.1.0.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.2/maven-archiver-3.6.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.jar

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.27/plexus-interpolation-1.27.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/3.1.0/file-management-3.1.0.jar (36 kB at 605 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.9.2/plexus-archiver-4.9.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-archiver/3.6.2/maven-archiver-3.6.2.jar (27 kB at 348 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.4.2/plexus-io-3.4.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-io/3.4.2/plexus-io-3.4.2.jar (79 kB at 585 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.26.1/commons-compress-1.26.1.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-interpolation/1.27/plexus-interpolation-1.27.jar (86 kB at 572 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.14.0/commons-lang3-3.14.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-utils/4.0.1/plexus-utils-4.0.1.jar (193 kB at 1.2 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.16.1/commons-codec-1.16.1.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-archiver/4.9.2/plexus-archiver-4.9.2.jar (225 kB at 858 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.16.1/commons-io-2.16.1.jar (509 kB at 1.6 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.9/xz-1.9.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/iq80/snappy/snappy/0.4/snappy-0.4.jar (58 kB at 161 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.5-11/zstd-jni-1.5.5-11.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/tukaani/xz/1.9/xz-1.9.jar (116 kB at 304 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-lang3/3.14.0/commons-lang3-3.14.0.jar (658 kB at 1.2 MB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.26.1/commons-compress-1.26.1.jar (1.1 MB at 1.8 MB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.16.1/commons-codec-1.16.1.jar (365 kB at 589 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/com/github/luben/zstd-jni/1.5.5-11/zstd-jni-1.5.5-11.jar (6.8 MB at 5.9 MB/s)

## [INFO] Building jar: /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar

## [INFO]

## [INFO] --- spring-boot-maven-plugin:3.4.3:repackage (repackage) @ prac ---

## Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/3.4.3/spring-boot-buildpack-platform-3.4.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/3.4.3/spring-boot-buildpack-platform-3.4.3.pom (3.2 kB at 107 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.18.2/jackson-databind-2.18.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.18.2/jackson-databind-2.18.2.pom (21 kB at 574 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-base/2.18.2/jackson-base-2.18.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/jackson-base/2.18.2/jackson-base-2.18.2.pom (12 kB at 332 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.18.2/jackson-annotations-2.18.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.18.2/jackson-annotations-2.18.2.pom (7.1 kB at 182 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.18.2/jackson-core-2.18.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.18.2/jackson-core-2.18.2.pom (10 kB at 334 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.18.2/jackson-module-parameter-names-2.18.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.18.2/jackson-module-parameter-names-2.18.2.pom (4.2 kB at 114 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-modules-java8/2.18.2/jackson-modules-java8-2.18.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-modules-java8/2.18.2/jackson-modules-java8-2.18.2.pom (3.3 kB at 103 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.13.0/jna-platform-5.13.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.13.0/jna-platform-5.13.0.pom (2.3 kB at 64 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.13.0/jna-5.13.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.13.0/jna-5.13.0.pom (2.0 kB at 68 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.25.0/commons-compress-1.25.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.25.0/commons-compress-1.25.0.pom (22 kB at 603 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.4.2/httpclient5-5.4.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.4.2/httpclient5-5.4.2.pom (6.1 kB at 148 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5-parent/5.4.2/httpclient5-parent-5.4.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5-parent/5.4.2/httpclient5-parent-5.4.2.pom (16 kB at 543 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-parent/13/httpcomponents-parent-13.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcomponents-parent/13/httpcomponents-parent-13.pom (30 kB at 795 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/apache/27/apache-27.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/apache/27/apache-27.pom (20 kB at 657 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.11.0/junit-bom-5.11.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/junit/junit-bom/5.11.0/junit-bom-5.11.0.pom (5.6 kB at 20 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.3.3/httpcore5-5.3.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.3.3/httpcore5-5.3.3.pom (3.9 kB at 120 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-parent/5.3.3/httpcore5-parent-5.3.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-parent/5.3.3/httpcore5-parent-5.3.3.pom (14 kB at 465 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.3.3/httpcore5-h2-5.3.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.3.3/httpcore5-h2-5.3.3.pom (3.6 kB at 110 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.pom (2.8 kB at 97 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.pom (3.6 kB at 121 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-master/4.7.2/antlr4-master-4.7.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-master/4.7.2/antlr4-master-4.7.2.pom (4.4 kB at 147 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.pom (4.3 kB at 138 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/3.4.3/spring-boot-loader-tools-3.4.3.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/3.4.3/spring-boot-loader-tools-3.4.3.pom (2.2 kB at 75 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.3.2/maven-common-artifact-filters-3.3.2.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.3.2/maven-common-artifact-filters-3.3.2.pom (5.3 kB at 182 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/37/maven-shared-components-37.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-components/37/maven-shared-components-37.pom (4.9 kB at 169 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/37/maven-parent-37.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven-parent/37/maven-parent-37.pom (46 kB at 1.3 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.5.0/maven-shade-plugin-3.5.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.5.0/maven-shade-plugin-3.5.0.pom (12 kB at 388 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.32/slf4j-api-1.7.32.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.32/slf4j-api-1.7.32.pom (3.8 kB at 124 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.7.32/slf4j-parent-1.7.32.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.7.32/slf4j-parent-1.7.32.pom (14 kB at 445 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.5/asm-9.5.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.5/asm-9.5.pom (2.4 kB at 61 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.5/asm-commons-9.5.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.5/asm-commons-9.5.pom (2.8 kB at 82 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.5/asm-tree-9.5.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.5/asm-tree-9.5.pom (2.6 kB at 93 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.pom (4.6 kB at 139 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.2.1/maven-dependency-tree-3.2.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.2.1/maven-dependency-tree-3.2.1.pom (6.2 kB at 189 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.0.v20140518/aether-util-1.0.0.v20140518.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.0.v20140518/aether-util-1.0.0.v20140518.pom (2.2 kB at 59 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether/1.0.0.v20140518/aether-1.0.0.v20140518.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether/1.0.0.v20140518/aether-1.0.0.v20140518.pom (30 kB at 914 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.0.v20140518/aether-api-1.0.0.v20140518.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.0.v20140518/aether-api-1.0.0.v20140518.pom (1.9 kB at 68 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.13.0/commons-io-2.13.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.13.0/commons-io-2.13.0.pom (20 kB at 564 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/58/commons-parent-58.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/58/commons-parent-58.pom (83 kB at 1.6 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.8.0/jdependency-2.8.0.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.8.0/jdependency-2.8.0.pom (14 kB at 421 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-collections4/4.4/commons-collections4-4.4.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-collections4/4.4/commons-collections4-4.4.pom (24 kB at 595 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/48/commons-parent-48.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-parent/48/commons-parent-48.pom (72 kB at 819 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/3.4.3/spring-boot-buildpack-platform-3.4.3.jar

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.18.2/jackson-databind-2.18.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.18.2/jackson-core-2.18.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.18.2/jackson-annotations-2.18.2.jar

## Downloading from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.18.2/jackson-module-parameter-names-2.18.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.18.2/jackson-annotations-2.18.2.jar (78 kB at 714 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.13.0/jna-platform-5.13.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/module/jackson-module-parameter-names/2.18.2/jackson-module-parameter-names-2.18.2.jar (10 kB at 94 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.13.0/jna-5.13.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-buildpack-platform/3.4.3/spring-boot-buildpack-platform-3.4.3.jar (298 kB at 2.3 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.25.0/commons-compress-1.25.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-core/2.18.2/jackson-core-2.18.2.jar (598 kB at 1.3 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.4.2/httpclient5-5.4.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna-platform/5.13.0/jna-platform-5.13.0.jar (1.4 MB at 2.4 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.3.3/httpcore5-5.3.3.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-compress/1.25.0/commons-compress-1.25.0.jar (1.1 MB at 1.8 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.3.3/httpcore5-h2-5.3.3.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.18.2/jackson-databind-2.18.2.jar (1.7 MB at 2.4 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5-h2/5.3.3/httpcore5-h2-5.3.3.jar (241 kB at 315 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/tomlj/tomlj/1.0.0/tomlj-1.0.0.jar (157 kB at 198 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/core5/httpcore5/5.3.3/httpcore5-5.3.3.jar (907 kB at 1.1 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/3.4.3/spring-boot-loader-tools-3.4.3.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/com/google/code/findbugs/jsr305/3.0.2/jsr305-3.0.2.jar (20 kB at 24 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.3.2/maven-common-artifact-filters-3.3.2.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/client5/httpclient5/5.4.2/httpclient5-5.4.2.jar (909 kB at 1.0 MB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.5.0/maven-shade-plugin-3.5.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.3.2/maven-common-artifact-filters-3.3.2.jar (58 kB at 64 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.5/asm-9.5.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.jar (338 kB at 352 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.5/asm-commons-9.5.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-shade-plugin/3.5.0/maven-shade-plugin-3.5.0.jar (147 kB at 152 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.5/asm-tree-9.5.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/springframework/boot/spring-boot-loader-tools/3.4.3/spring-boot-loader-tools-3.4.3.jar (465 kB at 471 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-commons/9.5/asm-commons-9.5.jar (72 kB at 71 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.2.1/maven-dependency-tree-3.2.1.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm-tree/9.5/asm-tree-9.5.jar (52 kB at 51 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.0.v20140518/aether-util-1.0.0.v20140518.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/9.5/asm-9.5.jar (122 kB at 117 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.0.v20140518/aether-api-1.0.0.v20140518.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.2.1/maven-dependency-tree-3.2.1.jar (43 kB at 40 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.13.0/commons-io-2.13.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-api/1.0.0.v20140518/aether-api-1.0.0.v20140518.jar (136 kB at 118 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.8.0/jdependency-2.8.0.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/1.0.0.v20140518/aether-util-1.0.0.v20140518.jar (146 kB at 126 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-collections4/4.4/commons-collections4-4.4.jar

## Downloaded from central: https://repo.maven.apache.org/maven2/org/jdom/jdom2/2.0.6.1/jdom2-2.0.6.1.jar (328 kB at 280 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/commons-io/commons-io/2.13.0/commons-io-2.13.0.jar (484 kB at 388 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/net/java/dev/jna/jna/5.13.0/jna-5.13.0.jar (1.9 MB at 1.5 MB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/vafer/jdependency/2.8.0/jdependency-2.8.0.jar (233 kB at 181 kB/s)

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/commons/commons-collections4/4.4/commons-collections4-4.4.jar (752 kB at 557 kB/s)

## [INFO] Replacing main artifact /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar with repackaged archive, adding nested dependencies in BOOT-INF/.

## [INFO] The original artifact has been renamed to /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar.original

## [INFO] ------------------------------------------------------------------------

## [INFO] BUILD SUCCESS

## [INFO] ------------------------------------------------------------------------

## [INFO] Total time: 16.390 s

## [INFO] Finished at: 2025-02-25T21:20:04+09:00

## [INFO] ------------------------------------------------------------------------

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App

## Error: Could not find or load main class com.mycompany.app.App

## Caused by: java.lang.ClassNotFoundException: com.mycompany.app.App

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1.-SNAPSHOT.jar com.org.app.prac

## Error: Could not find or load main class com.org.app.prac

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1.SNAPSHOT.jar com.org.app.prac

## Error: Could not find or load main class com.org.app.prac

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1.SNAPSHOT.jar com.org.app.prac.PracApplication

## Error: Could not find or load main class com.org.app.prac.PracApplication

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac.PracApplication

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1.SNAPSHOT.jar com.org.app.prac.PracApplication

## Error: Could not find or load main class com.org.app.prac.PracApplication

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac.PracApplication

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1.SNAPSHOT.jar java.com.org.app.prac.PracApplic

## ation

## Error: Could not find or load main class java.com.org.app.prac.PracApplication

## Caused by: java.lang.ClassNotFoundException: java.com.org.app.prac.PracApplication

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1-SNAPSHOT.jar com.org.app.prac.PracApplication

## Error: Could not find or load main class com.org.app.prac.PracApplication

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac.PracApplication

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1-SNAPSHOT.jar com.org.app.prac.PracApplication

## Error: Could not find or load main class com.org.app.prac.PracApplication

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac.PracApplication

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1-SNAPSHOT.jar com.org.app.prac.PracApplication

## Error: Could not find or load main class com.org.app.prac.PracApplication

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac.PracApplication

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -cp target/prac-0.0.1-SNAPSHOT.jar com.org.app.prac.PracApplication

## Error: Could not find or load main class com.org.app.prac.PracApplication

## Caused by: java.lang.ClassNotFoundException: com.org.app.prac.PracApplication

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ Main-Class: com.org.app.prac.PracApplication

##

## Main-Class:: command not found

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ jar tf target/prac-0.0.1-SNAPSHOT.jar | grep META-INF/MANIFEST.MF

##

## Command 'jar' not found, but can be installed with:

##

## sudo apt install openjdk-11-jdk-headless # version 11.0.24+8-1ubuntu3~20.04, or

## sudo apt install default-jdk # version 2:1.11-72

## sudo apt install openjdk-16-jdk-headless # version 16.0.1+9-1~20.04

## sudo apt install openjdk-17-jdk-headless # version 17.0.12+7-1ubuntu2~20.04

## sudo apt install openjdk-21-jdk-headless # version 21.0.4+7-1ubuntu2~20.04

## sudo apt install openjdk-8-jdk-headless # version 8u422-b05-1~20.04

## sudo apt install fastjar # version 2:0.98-6build1

## sudo apt install openjdk-13-jdk-headless # version 13.0.7+5-0ubuntu1~20.04

##

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ ls

## HELP.md mvnw mvnw.cmd pom.xml src target

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ sudo apt update

## [sudo] password for sudeep:

## 432Sorry, try again.

## [sudo] password for sudeep:

## Sorry, try again.

## [sudo] password for sudeep:

## Hit:1 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal InRelease

## Hit:2 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal-updates InRelease

## Hit:3 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal-backports InRelease

## Hit:4 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal-security InRelease

## Hit:5 https://dl.yarnpkg.com/debian stable InRelease

## Hit:6 https://packages.microsoft.com/repos/code stable InRelease

## Hit:7 https://deb.nodesource.com/node_17.x focal InRelease

## Get:8 https://download.docker.com/linux/ubuntu focal InRelease [57.7 kB]

## Hit:9 https://dl.google.com/linux/chrome/deb stable InRelease

## Fetched 57.7 kB in 1s (45.8 kB/s)

## Reading package lists... Done

## Building dependency tree

## Reading state information... Done

## All packages are up to date.

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ sudo apt install openjdk-17-jdk

## Reading package lists... Done

## Building dependency tree

## Reading state information... Done

## The following additional packages will be installed:

## libice-dev libpthread-stubs0-dev libsm-dev libx11-dev libxau-dev libxcb1-dev libxdmcp-dev libxt-dev openjdk-17-jdk-headless

## openjdk-17-jre x11proto-core-dev x11proto-dev xorg-sgml-doctools xtrans-dev

## Suggested packages:

## libice-doc libsm-doc libx11-doc libxcb-doc libxt-doc openjdk-17-demo openjdk-17-source visualvm

## The following NEW packages will be installed:

## libice-dev libpthread-stubs0-dev libsm-dev libx11-dev libxau-dev libxcb1-dev libxdmcp-dev libxt-dev openjdk-17-jdk

## openjdk-17-jdk-headless openjdk-17-jre x11proto-core-dev x11proto-dev xorg-sgml-doctools xtrans-dev

## 0 upgraded, 15 newly installed, 0 to remove and 0 not upgraded.

## Need to get 75.1 MB of archives.

## After this operation, 88.2 MB of additional disk space will be used.

## Do you want to continue? [Y/n] Y

## Get:1 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 xorg-sgml-doctools all 1:1.11-1 [12.9 kB]

## Get:2 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 x11proto-dev all 2019.2-1ubuntu1 [594 kB]

## Get:3 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 x11proto-core-dev all 2019.2-1ubuntu1 [2,620 B]

## Get:4 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 libice-dev amd64 2:1.0.10-0ubuntu1 [47.8 kB]

## Get:5 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 libpthread-stubs0-dev amd64 0.4-1 [5,384 B]

## Get:6 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 libsm-dev amd64 2:1.2.3-1 [17.0 kB]

## Get:7 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 libxau-dev amd64 1:1.0.9-0ubuntu1 [9,552 B]

## Get:8 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 libxdmcp-dev amd64 1:1.1.3-0ubuntu1 [25.3 kB]

## Get:9 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 xtrans-dev all 1.4.0-1 [68.9 kB]

## Get:10 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 libxcb1-dev amd64 1.14-2 [80.5 kB]

## Get:11 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal-updates/main amd64 libx11-dev amd64 2:1.6.9-2ubuntu1.6 [648 kB]

## Get:12 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal/main amd64 libxt-dev amd64 1:1.1.5-1 [395 kB]

## Get:13 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal-updates/universe amd64 openjdk-17-jre amd64 17.0.14+7-1~20.04 [209 kB]

## Get:14 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal-updates/universe amd64 openjdk-17-jdk-headless amd64 17.0.14+7-1~20.04 [71.5 MB]

## Get:15 http://ftp.tsukuba.wide.ad.jp/Linux/ubuntu focal-updates/universe amd64 openjdk-17-jdk amd64 17.0.14+7-1~20.04 [1,526 kB]

## Fetched 75.1 MB in 10s (7,345 kB/s)

## Selecting previously unselected package xorg-sgml-doctools.

## (Reading database ... 218336 files and directories currently installed.)

## Preparing to unpack .../00-xorg-sgml-doctools_1%3a1.11-1_all.deb ...

## Unpacking xorg-sgml-doctools (1:1.11-1) ...

## Selecting previously unselected package x11proto-dev.

## Preparing to unpack .../01-x11proto-dev_2019.2-1ubuntu1_all.deb ...

## Unpacking x11proto-dev (2019.2-1ubuntu1) ...

## Selecting previously unselected package x11proto-core-dev.

## Preparing to unpack .../02-x11proto-core-dev_2019.2-1ubuntu1_all.deb ...

## Unpacking x11proto-core-dev (2019.2-1ubuntu1) ...

## Selecting previously unselected package libice-dev:amd64.

## Preparing to unpack .../03-libice-dev_2%3a1.0.10-0ubuntu1_amd64.deb ...

## Unpacking libice-dev:amd64 (2:1.0.10-0ubuntu1) ...

## Selecting previously unselected package libpthread-stubs0-dev:amd64.

## Preparing to unpack .../04-libpthread-stubs0-dev_0.4-1_amd64.deb ...

## Unpacking libpthread-stubs0-dev:amd64 (0.4-1) ...

## Selecting previously unselected package libsm-dev:amd64.

## Preparing to unpack .../05-libsm-dev_2%3a1.2.3-1_amd64.deb ...

## Unpacking libsm-dev:amd64 (2:1.2.3-1) ...

## Selecting previously unselected package libxau-dev:amd64.

## Preparing to unpack .../06-libxau-dev_1%3a1.0.9-0ubuntu1_amd64.deb ...

## Unpacking libxau-dev:amd64 (1:1.0.9-0ubuntu1) ...

## Selecting previously unselected package libxdmcp-dev:amd64.

## Preparing to unpack .../07-libxdmcp-dev_1%3a1.1.3-0ubuntu1_amd64.deb ...

## Unpacking libxdmcp-dev:amd64 (1:1.1.3-0ubuntu1) ...

## Selecting previously unselected package xtrans-dev.

## Preparing to unpack .../08-xtrans-dev_1.4.0-1_all.deb ...

## Unpacking xtrans-dev (1.4.0-1) ...

## Selecting previously unselected package libxcb1-dev:amd64.

## Preparing to unpack .../09-libxcb1-dev_1.14-2_amd64.deb ...

## Unpacking libxcb1-dev:amd64 (1.14-2) ...

## Selecting previously unselected package libx11-dev:amd64.

## Preparing to unpack .../10-libx11-dev_2%3a1.6.9-2ubuntu1.6_amd64.deb ...

## Unpacking libx11-dev:amd64 (2:1.6.9-2ubuntu1.6) ...

## Selecting previously unselected package libxt-dev:amd64.

## Preparing to unpack .../11-libxt-dev_1%3a1.1.5-1_amd64.deb ...

## Unpacking libxt-dev:amd64 (1:1.1.5-1) ...

## Selecting previously unselected package openjdk-17-jre:amd64.

## Preparing to unpack .../12-openjdk-17-jre_17.0.14+7-1~20.04_amd64.deb ...

## Unpacking openjdk-17-jre:amd64 (17.0.14+7-1~20.04) ...

## Selecting previously unselected package openjdk-17-jdk-headless:amd64.

## Preparing to unpack .../13-openjdk-17-jdk-headless_17.0.14+7-1~20.04_amd64.deb ...

## Unpacking openjdk-17-jdk-headless:amd64 (17.0.14+7-1~20.04) ...

## Selecting previously unselected package openjdk-17-jdk:amd64.

## Preparing to unpack .../14-openjdk-17-jdk_17.0.14+7-1~20.04_amd64.deb ...

## Unpacking openjdk-17-jdk:amd64 (17.0.14+7-1~20.04) ...

## Setting up openjdk-17-jre:amd64 (17.0.14+7-1~20.04) ...

## Setting up libpthread-stubs0-dev:amd64 (0.4-1) ...

## Setting up xtrans-dev (1.4.0-1) ...

## Setting up openjdk-17-jdk-headless:amd64 (17.0.14+7-1~20.04) ...

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jar to provide /usr/bin/jar (jar) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jarsigner to provide /usr/bin/jarsigner (jarsigner) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/javac to provide /usr/bin/javac (javac) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/javadoc to provide /usr/bin/javadoc (javadoc) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/javap to provide /usr/bin/javap (javap) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jcmd to provide /usr/bin/jcmd (jcmd) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jdb to provide /usr/bin/jdb (jdb) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jdeprscan to provide /usr/bin/jdeprscan (jdeprscan) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jdeps to provide /usr/bin/jdeps (jdeps) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jfr to provide /usr/bin/jfr (jfr) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jimage to provide /usr/bin/jimage (jimage) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jinfo to provide /usr/bin/jinfo (jinfo) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jlink to provide /usr/bin/jlink (jlink) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jmap to provide /usr/bin/jmap (jmap) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jmod to provide /usr/bin/jmod (jmod) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jps to provide /usr/bin/jps (jps) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jrunscript to provide /usr/bin/jrunscript (jrunscript) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jshell to provide /usr/bin/jshell (jshell) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jstack to provide /usr/bin/jstack (jstack) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jstat to provide /usr/bin/jstat (jstat) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jstatd to provide /usr/bin/jstatd (jstatd) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/serialver to provide /usr/bin/serialver (serialver) in auto mode

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jhsdb to provide /usr/bin/jhsdb (jhsdb) in auto mode

## Setting up xorg-sgml-doctools (1:1.11-1) ...

## Setting up openjdk-17-jdk:amd64 (17.0.14+7-1~20.04) ...

## update-alternatives: using /usr/lib/jvm/java-17-openjdk-amd64/bin/jconsole to provide /usr/bin/jconsole (jconsole) in auto mode

## Processing triggers for sgml-base (1.29.1) ...

## Setting up x11proto-dev (2019.2-1ubuntu1) ...

## Processing triggers for desktop-file-utils (0.24-1ubuntu3) ...

## Processing triggers for mime-support (3.64ubuntu1) ...

## Setting up libxau-dev:amd64 (1:1.0.9-0ubuntu1) ...

## Processing triggers for hicolor-icon-theme (0.17-2) ...

## Setting up libice-dev:amd64 (2:1.0.10-0ubuntu1) ...

## Processing triggers for gnome-menus (3.36.0-1ubuntu1) ...

## Setting up libsm-dev:amd64 (2:1.2.3-1) ...

## Processing triggers for man-db (2.9.1-1) ...

## Setting up libxdmcp-dev:amd64 (1:1.1.3-0ubuntu1) ...

## Setting up x11proto-core-dev (2019.2-1ubuntu1) ...

## Setting up libxcb1-dev:amd64 (1.14-2) ...

## Setting up libx11-dev:amd64 (2:1.6.9-2ubuntu1.6) ...

## Setting up libxt-dev:amd64 (1:1.1.5-1) ...

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ jar --version

## jar 17.0.14

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ jar tf target/prac-0.0.1-SNAPSHOT.jar | grep META-INF/MANIFEST.MF

## META-INF/MANIFEST.MF

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ jar xf target/prac-0.0.1-SNAPSHOT.jar META-INF/MANIFEST.MF

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ cat META-INF/MANIFEST.MF

## Manifest-Version: 1.0

## Created-By: Maven JAR Plugin 3.4.2

## Build-Jdk-Spec: 17

## Implementation-Title: prac

## Implementation-Version: 0.0.1-SNAPSHOT

## Main-Class: org.springframework.boot.loader.launch.JarLauncher

## Start-Class: com.org.app.prac.PracApplication

## Spring-Boot-Version: 3.4.3

## Spring-Boot-Classes: BOOT-INF/classes/

## Spring-Boot-Lib: BOOT-INF/lib/

## Spring-Boot-Classpath-Index: BOOT-INF/classpath.idx

## Spring-Boot-Layers-Index: BOOT-INF/layers.idx

##

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ Main-Class: com.org.app.prac.PracApplication

## Main-Class:: command not found

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -jar target/prac-0.0.1-SNAPSHOT.jar

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T22:03:32.598+09:00 INFO 45350 --- [prac] [ main] com.org.app.prac.PracApplication : Starting PracApplication v0.0.1-SNAPSHOT using Java 17.0.14 with PID 45350 (/home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar started by sudeep in /home/sudeep/Documents/study/java/prac)

## 2025-02-25T22:03:32.603+09:00 INFO 45350 --- [prac] [ main] com.org.app.prac.PracApplication : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T22:03:33.625+09:00 INFO 45350 --- [prac] [ main] com.org.app.prac.PracApplication : Started PracApplication in 1.808 seconds (process running for 2.761)

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ netstat -tulnp | grep 8080

## (Not all processes could be identified, non-owned process info

## will not be shown, you would have to be root to see it all.)

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ sudo netstat -tulnp | grep 8080

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ ss -tulnp | grep 8080

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ grep -r "spring-boot-starter-web" pom.xml

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ mvn clean package

## SHOT.jar

## [INFO] Scanning for projects...

## [INFO]

## [INFO] --------------------------< com.org.app:prac >--------------------------

## [INFO] Building prac 0.0.1-SNAPSHOT

## [INFO] --------------------------------[ jar ]---------------------------------

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-clean-plugin/3.4.1/maven-clean-plugin-3.4.1.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-clean-plugin/3.4.1/maven-clean-plugin-3.4.1.pom (5.6 kB at 13 kB/s)

## Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/43/maven-plugins-43.pom

## Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/plugins/maven-plugins/43/maven-plugins-43.pom (7.5 kB at 108 kB/s)

## [INFO]

## [INFO] --- maven-clean-plugin:3.4.1:clean (default-clean) @ prac ---

## [INFO] Deleting /home/sudeep/Documents/study/java/prac/target

## [INFO]

## [INFO] --- maven-resources-plugin:3.3.1:resources (default-resources) @ prac ---

## [INFO] Copying 1 resource from src/main/resources to target/classes

## [INFO] Copying 0 resource from src/main/resources to target/classes

## [INFO]

## [INFO] --- maven-compiler-plugin:3.13.0:compile (default-compile) @ prac ---

## [INFO] Recompiling the module because of changed source code.

## [INFO] Compiling 1 source file with javac [debug parameters release 17] to target/classes

## [INFO]

## [INFO] --- maven-resources-plugin:3.3.1:testResources (default-testResources) @ prac ---

## [INFO] skip non existing resourceDirectory /home/sudeep/Documents/study/java/prac/src/test/resources

## [INFO]

## [INFO] --- maven-compiler-plugin:3.13.0:testCompile (default-testCompile) @ prac ---

## [INFO] Recompiling the module because of changed dependency.

## [INFO] Compiling 1 source file with javac [debug parameters release 17] to target/test-classes

## [INFO]

## [INFO] --- maven-surefire-plugin:3.5.2:test (default-test) @ prac ---

## [INFO] Using auto detected provider org.apache.maven.surefire.junitplatform.JUnitPlatformProvider

## [INFO]

## [INFO] -------------------------------------------------------

## [INFO] T E S T S

## [INFO] -------------------------------------------------------

## [INFO] Running com.org.app.prac.PracApplicationTests

## 22:09:07.619 [main] INFO org.springframework.test.context.support.AnnotationConfigContextLoaderUtils -- Could not detect default configuration classes for test class [com.org.app.prac.PracApplicationTests]: PracApplicationTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.

## 22:09:07.819 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper -- Found @SpringBootConfiguration com.org.app.prac.PracApplication for test class com.org.app.prac.PracApplicationTests

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T22:09:08.560+09:00 INFO 48430 --- [prac] [ main] com.org.app.prac.PracApplicationTests : Starting PracApplicationTests using Java 17.0.14 with PID 48430 (started by sudeep in /home/sudeep/Documents/study/java/prac)

## 2025-02-25T22:09:08.562+09:00 INFO 48430 --- [prac] [ main] com.org.app.prac.PracApplicationTests : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T22:09:10.144+09:00 INFO 48430 --- [prac] [ main] com.org.app.prac.PracApplicationTests : Started PracApplicationTests in 2.0 seconds (process running for 3.93)

## OpenJDK 64-Bit Server VM warning: Sharing is only supported for boot loader classes because bootstrap classpath has been appended

## [INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 4.048 s -- in com.org.app.prac.PracApplicationTests

## [INFO]

## [INFO] Results:

## [INFO]

## [INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

## [INFO]

## [INFO]

## [INFO] --- maven-jar-plugin:3.4.2:jar (default-jar) @ prac ---

## [INFO] Building jar: /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar

## [INFO]

## [INFO] --- spring-boot-maven-plugin:3.4.3:repackage (repackage) @ prac ---

## [INFO] Replacing main artifact /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar with repackaged archive, adding nested dependencies in BOOT-INF/.

## [INFO] The original artifact has been renamed to /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar.original

## [INFO] ------------------------------------------------------------------------

## [INFO] BUILD SUCCESS

## [INFO] ------------------------------------------------------------------------

## [INFO] Total time: 11.439 s

## [INFO] Finished at: 2025-02-25T22:09:12+09:00

## [INFO] ------------------------------------------------------------------------

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -jar target/prac-0.0.1-SNAPSHOT.jar

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T22:09:14.610+09:00 INFO 48582 --- [prac] [ main] com.org.app.prac.PracApplication : Starting PracApplication v0.0.1-SNAPSHOT using Java 17.0.14 with PID 48582 (/home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar started by sudeep in /home/sudeep/Documents/study/java/prac)

## 2025-02-25T22:09:14.615+09:00 INFO 48582 --- [prac] [ main] com.org.app.prac.PracApplication : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T22:09:16.563+09:00 INFO 48582 --- [prac] [ main] o.s.b.w.embedded.tomcat.TomcatWebServer : Tomcat initialized with port 8080 (http)

## 2025-02-25T22:09:16.611+09:00 INFO 48582 --- [prac] [ main] o.apache.catalina.core.StandardService : Starting service [Tomcat]

## 2025-02-25T22:09:16.611+09:00 INFO 48582 --- [prac] [ main] o.apache.catalina.core.StandardEngine : Starting Servlet engine: [Apache Tomcat/10.1.36]

## 2025-02-25T22:09:16.709+09:00 INFO 48582 --- [prac] [ main] o.a.c.c.C.[Tomcat].[localhost].[/] : Initializing Spring embedded WebApplicationContext

## 2025-02-25T22:09:16.711+09:00 INFO 48582 --- [prac] [ main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1965 ms

## 2025-02-25T22:09:17.376+09:00 INFO 48582 --- [prac] [ main] o.s.b.w.embedded.tomcat.TomcatWebServer : Tomcat started on port 8080 (http) with context path '/'

## 2025-02-25T22:09:17.425+09:00 INFO 48582 --- [prac] [ main] com.org.app.prac.PracApplication : Started PracApplication in 3.657 seconds (process running for 4.63)

## 2025-02-25T22:09:25.828+09:00 INFO 48582 --- [prac] [nio-8080-exec-1] o.a.c.c.C.[Tomcat].[localhost].[/] : Initializing Spring DispatcherServlet 'dispatcherServlet'

## 2025-02-25T22:09:25.829+09:00 INFO 48582 --- [prac] [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet : Initializing Servlet 'dispatcherServlet'

## 2025-02-25T22:09:25.831+09:00 INFO 48582 --- [prac] [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet : Completed initialization in 1 ms

## ^C2025-02-25T22:13:16.385+09:00 INFO 48582 --- [prac] [ionShutdownHook] o.s.b.w.e.tomcat.GracefulShutdown : Commencing graceful shutdown. Waiting for active requests to complete

## 2025-02-25T22:13:16.420+09:00 INFO 48582 --- [prac] [tomcat-shutdown] o.s.b.w.e.tomcat.GracefulShutdown : Graceful shutdown complete

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ ^C

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ grep -r "@RestController" src/main/java

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ mvn clean package

## SHOT.jar

## [INFO] Scanning for projects...

## [INFO]

## [INFO] --------------------------< com.org.app:prac >--------------------------

## [INFO] Building prac 0.0.1-SNAPSHOT

## [INFO] --------------------------------[ jar ]---------------------------------

## [INFO]

## [INFO] --- maven-clean-plugin:3.4.1:clean (default-clean) @ prac ---

## [INFO] Deleting /home/sudeep/Documents/study/java/prac/target

## [INFO]

## [INFO] --- maven-resources-plugin:3.3.1:resources (default-resources) @ prac ---

## [INFO] Copying 1 resource from src/main/resources to target/classes

## [INFO] Copying 0 resource from src/main/resources to target/classes

## [INFO]

## [INFO] --- maven-compiler-plugin:3.13.0:compile (default-compile) @ prac ---

## [INFO] Recompiling the module because of changed source code.

## [INFO] Compiling 2 source files with javac [debug parameters release 17] to target/classes

## [INFO]

## [INFO] --- maven-resources-plugin:3.3.1:testResources (default-testResources) @ prac ---

## [INFO] skip non existing resourceDirectory /home/sudeep/Documents/study/java/prac/src/test/resources

## [INFO]

## [INFO] --- maven-compiler-plugin:3.13.0:testCompile (default-testCompile) @ prac ---

## [INFO] Recompiling the module because of changed dependency.

## [INFO] Compiling 1 source file with javac [debug parameters release 17] to target/test-classes

## [INFO]

## [INFO] --- maven-surefire-plugin:3.5.2:test (default-test) @ prac ---

## [INFO] Using auto detected provider org.apache.maven.surefire.junitplatform.JUnitPlatformProvider

## [INFO]

## [INFO] -------------------------------------------------------

## [INFO] T E S T S

## [INFO] -------------------------------------------------------

## [INFO] Running com.org.app.prac.PracApplicationTests

## 22:13:01.839 [main] INFO org.springframework.test.context.support.AnnotationConfigContextLoaderUtils -- Could not detect default configuration classes for test class [com.org.app.prac.PracApplicationTests]: PracApplicationTests does not declare any static, non-private, non-final, nested classes annotated with @Configuration.

## 22:13:02.097 [main] INFO org.springframework.boot.test.context.SpringBootTestContextBootstrapper -- Found @SpringBootConfiguration com.org.app.prac.PracApplication for test class com.org.app.prac.PracApplicationTests

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T22:13:02.783+09:00 INFO 50730 --- [prac] [ main] com.org.app.prac.PracApplicationTests : Starting PracApplicationTests using Java 17.0.14 with PID 50730 (started by sudeep in /home/sudeep/Documents/study/java/prac)

## 2025-02-25T22:13:02.785+09:00 INFO 50730 --- [prac] [ main] com.org.app.prac.PracApplicationTests : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T22:13:04.345+09:00 INFO 50730 --- [prac] [ main] com.org.app.prac.PracApplicationTests : Started PracApplicationTests in 1.986 seconds (process running for 4.078)

## OpenJDK 64-Bit Server VM warning: Sharing is only supported for boot loader classes because bootstrap classpath has been appended

## [INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 3.961 s -- in com.org.app.prac.PracApplicationTests

## [INFO]

## [INFO] Results:

## [INFO]

## [INFO] Tests run: 1, Failures: 0, Errors: 0, Skipped: 0

## [INFO]

## [INFO]

## [INFO] --- maven-jar-plugin:3.4.2:jar (default-jar) @ prac ---

## [INFO] Building jar: /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar

## [INFO]

## [INFO] --- spring-boot-maven-plugin:3.4.3:repackage (repackage) @ prac ---

## [INFO] Replacing main artifact /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar with repackaged archive, adding nested dependencies in BOOT-INF/.

## [INFO] The original artifact has been renamed to /home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar.original

## [INFO] ------------------------------------------------------------------------

## [INFO] BUILD SUCCESS

## [INFO] ------------------------------------------------------------------------

## [INFO] Total time: 11.064 s

## [INFO] Finished at: 2025-02-25T22:13:06+09:00

## [INFO] ------------------------------------------------------------------------

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -jar target/prac-0.0.1-SNAPSHOT.jar

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T22:13:08.881+09:00 INFO 50872 --- [prac] [ main] com.org.app.prac.PracApplication : Starting PracApplication v0.0.1-SNAPSHOT using Java 17.0.14 with PID 50872 (/home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar started by sudeep in /home/sudeep/Documents/study/java/prac)

## 2025-02-25T22:13:08.888+09:00 INFO 50872 --- [prac] [ main] com.org.app.prac.PracApplication : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T22:13:10.385+09:00 INFO 50872 --- [prac] [ main] o.s.b.w.embedded.tomcat.TomcatWebServer : Tomcat initialized with port 8080 (http)

## 2025-02-25T22:13:10.409+09:00 INFO 50872 --- [prac] [ main] o.apache.catalina.core.StandardService : Starting service [Tomcat]

## 2025-02-25T22:13:10.410+09:00 INFO 50872 --- [prac] [ main] o.apache.catalina.core.StandardEngine : Starting Servlet engine: [Apache Tomcat/10.1.36]

## 2025-02-25T22:13:10.475+09:00 INFO 50872 --- [prac] [ main] o.a.c.c.C.[Tomcat].[localhost].[/] : Initializing Spring embedded WebApplicationContext

## 2025-02-25T22:13:10.477+09:00 INFO 50872 --- [prac] [ main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1469 ms

## 2025-02-25T22:13:11.169+09:00 WARN 50872 --- [prac] [ main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.context.ApplicationContextException: Failed to start bean 'webServerStartStop'

## 2025-02-25T22:13:11.212+09:00 INFO 50872 --- [prac] [ main] .s.b.a.l.ConditionEvaluationReportLogger :

##

## Error starting ApplicationContext. To display the condition evaluation report re-run your application with 'debug' enabled.

## 2025-02-25T22:13:11.293+09:00 ERROR 50872 --- [prac] [ main] o.s.b.d.LoggingFailureAnalysisReporter :

##

## ************\*\*\*************

## APPLICATION FAILED TO START

## ************\*\*\*************

##

## Description:

##

## Web server failed to start. Port 8080 was already in use.

##

## Action:

##

## Identify and stop the process that's listening on port 8080 or configure this application to listen on another port.

##

## sudeep@sudeep-Inspiron-3476:~/Documents/study/java/prac$ java -jar target/prac-0.0.1-SNAPSHOT.jar

##

## . \_**\_ \_ ** \_ \_

## /\\ / **_'_ ** \_ _(_)_ \_\_ \_\_ _ \ \ \ \

## ( ( )\_\__ | '_ | '_| | '_ \/ \_` | \ \ \ \

## \\/ _\_\_)| |_)| | | | | || (\_| | ) ) ) )

## ' |\_**\_| .**|_| |_|_| |_\_\_, | / / / /

## =========|\_|==============|_\_\_/=/_/_/_/

##

## :: Spring Boot :: (v3.4.3)

##

## 2025-02-25T22:13:22.153+09:00 INFO 51030 --- [prac] [ main] com.org.app.prac.PracApplication : Starting PracApplication v0.0.1-SNAPSHOT using Java 17.0.14 with PID 51030 (/home/sudeep/Documents/study/java/prac/target/prac-0.0.1-SNAPSHOT.jar started by sudeep in /home/sudeep/Documents/study/java/prac)

## 2025-02-25T22:13:22.157+09:00 INFO 51030 --- [prac] [ main] com.org.app.prac.PracApplication : No active profile set, falling back to 1 default profile: "default"

## 2025-02-25T22:13:23.499+09:00 INFO 51030 --- [prac] [ main] o.s.b.w.embedded.tomcat.TomcatWebServer : Tomcat initialized with port 8080 (http)

## 2025-02-25T22:13:23.521+09:00 INFO 51030 --- [prac] [ main] o.apache.catalina.core.StandardService : Starting service [Tomcat]

## 2025-02-25T22:13:23.521+09:00 INFO 51030 --- [prac] [ main] o.apache.catalina.core.StandardEngine : Starting Servlet engine: [Apache Tomcat/10.1.36]

## 2025-02-25T22:13:23.582+09:00 INFO 51030 --- [prac] [ main] o.a.c.c.C.[Tomcat].[localhost].[/] : Initializing Spring embedded WebApplicationContext

## 2025-02-25T22:13:23.584+09:00 INFO 51030 --- [prac] [ main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1337 ms

## 2025-02-25T22:13:24.104+09:00 INFO 51030 --- [prac] [ main] o.s.b.w.embedded.tomcat.TomcatWebServer : Tomcat started on port 8080 (http) with context path '/'

## 2025-02-25T22:13:24.139+09:00 INFO 51030 --- [prac] [ main] com.org.app.prac.PracApplication : Started PracApplication in 2.657 seconds (process running for 3.425)

## 2025-02-25T22:13:30.659+09:00 INFO 51030 --- [prac] [nio-8080-exec-1] o.a.c.c.C.[Tomcat].[localhost].[/] : Initializing Spring DispatcherServlet 'dispatcherServlet'

## 2025-02-25T22:13:30.659+09:00 INFO 51030 --- [prac] [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet : Initializing Servlet 'dispatcherServlet'

## 2025-02-25T22:13:30.661+09:00 INFO 51030 --- [prac] [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet : Completed initialization in 1 ms

##
