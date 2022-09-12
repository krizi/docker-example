# Commands

docker run -p 8080:8080 -d java-hello-world 

```
[INFO] Scanning for projects...
[INFO] 
[INFO] ------------------------------------------------------------------------
[INFO] Building java-hello-world 0.0.1-SNAPSHOT
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] >>> spring-boot-maven-plugin:2.7.3:run (default-cli) > test-compile @ java-hello-world >>>
[INFO] 
[INFO] --- maven-resources-plugin:3.2.0:resources (default-resources) @ java-hello-world ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Using 'UTF-8' encoding to copy filtered properties files.
[INFO] skip non existing resourceDirectory /tmp/src/main/resources
[INFO] skip non existing resourceDirectory /tmp/src/main/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.10.1:compile (default-compile) @ java-hello-world ---
[INFO] Changes detected - recompiling the module!
[INFO] Compiling 1 source file to /tmp/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:3.2.0:testResources (default-testResources) @ java-hello-world ---
[INFO] Using 'UTF-8' encoding to copy filtered resources.
[INFO] Using 'UTF-8' encoding to copy filtered properties files.
[INFO] skip non existing resourceDirectory /tmp/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.10.1:testCompile (default-testCompile) @ java-hello-world ---
[INFO] No sources to compile
[INFO] 
[INFO] <<< spring-boot-maven-plugin:2.7.3:run (default-cli) < test-compile @ java-hello-world <<<
[INFO] 
[INFO] 
[INFO] --- spring-boot-maven-plugin:2.7.3:run (default-cli) @ java-hello-world ---
[INFO] Attaching agents: []

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v2.7.3)

2022-09-12 15:05:42.676  INFO 45 --- [           main] ch.generali.example.Example              : Starting Example using Java 1.8.0_121 on 6617b3d845d0 with PID 45 (/tmp/target/classes started by root in /tmp)
2022-09-12 15:05:42.688  INFO 45 --- [           main] ch.generali.example.Example              : No active profile set, falling back to 1 default profile: "default"
2022-09-12 15:05:44.330  INFO 45 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2022-09-12 15:05:44.361  INFO 45 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2022-09-12 15:05:44.362  INFO 45 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.65]
2022-09-12 15:05:44.630  INFO 45 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2022-09-12 15:05:44.631  INFO 45 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1834 ms
2022-09-12 15:05:46.117  INFO 45 --- [           main] o.s.b.a.e.web.EndpointLinksResolver      : Exposing 1 endpoint(s) beneath base path '/actuator'
2022-09-12 15:05:46.303  INFO 45 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2022-09-12 15:05:46.333  INFO 45 --- [           main] ch.generali.example.Example              : Started Example in 4.176 seconds (JVM running for 4.728)

```



# see 
* https://spring.io/guides/gs/spring-boot/
* https://github.com/spring-guides/gs-spring-boot