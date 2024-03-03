# Modules

## spring-webmvc
* Check image of modules
* requires 
```
<dependency>
<groupId>org.springdoc</groupId>
<artifactId>springdoc-openapi-starter-webmvc-api</artifactId>
<version>2.3.0</version>
</dependency>
```
* just valid
  * JSON
  * YAML

## spring-webflux
* Check image of modules
* requires 
```
<dependency>
<groupId>org.springdoc</groupId>
<artifactId>springdoc-openapi-starter-webflux-api</artifactId>
<version>2.3.0</version>
</dependency>
```
* just valid
  * JSON
  * YAML

## Spring Boot Actuator support
* `springdoc.show-actuator=true`
  * Spring Boot Actuator endpoints are displayed
    * via
      * HTML
      * JSON
      * YAML
    * in a dedicated group
* `management.endpoints.web.exposure.include`
  * expose under Spring Boot Actuator's endpoint
* Check in the demo repo all the possible combinations!!

---

## Kotlin Support
* ‘s modules ==  Java based’s modules
* requires 
```
<dependency>
<groupId>com.fasterxml.jackson.module</groupId>
<artifactId>jackson-module-kotlin</artifactId>
</dependency>
```

# Note:
* Check 'spring-openapi-demos' repo, under the project 
  * '/springdoc-openapi-modules-webmvc' &
  * '/springdoc-openapi-modules-webflux' &
  * '/springdoc-openapi-modules-actuator' &
  * '/springdoc-openapi-modules-kotlin' &