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

## spring-security or spring-authorization-server
* `springdoc-openapi`
  * allows
    * ignoring `@AuthenticationPrincipal` of Spring Security      -- TODO: --
    * exposing Oauth2 endpoints of Spring Authorization Server    -- TODO: --

* if Spring Security or Spring Authorization Server &
  * `spring-boot-starter-web` & you just want OpenAPI → `springdoc-openapi-starter-webmvc-api`
  * `spring-boot-starter-web` & you want OpenAPI + SwaggerUI → `springdoc-openapi-starter-webmvc-ui`
  * `spring-boot-starter-webflux` & you just want OpenAPI → `springdoc-openapi-starter-webflux-api`
  * `spring-boot-starter-webflux` & you want OpenAPI + SwaggerUI → `springdoc-openapi-starter-webflux-ui`

## Kotlin Support
* ‘s modules ==  Java based’s modules
* requires 
```
<dependency>
<groupId>com.fasterxml.jackson.module</groupId>
<artifactId>jackson-module-kotlin</artifactId>
</dependency>
```

## spring-hateoas
* it requires Spring Boot
* If you need access to Open API endpoints (== JSON / YAML )→ `springdoc-openapi-starter-webmvc-api`
* If you need access to Swagger UI (== HTML )→ `springdoc-openapi-starter-webmvc-ui`

# Note:
* Check 'spring-openapi-demos' repo, under the project 
  * '/springdoc-openapi-modules-webmvc' &
  * '/springdoc-openapi-modules-webflux' &
  * '/springdoc-openapi-modules-actuator' &
  * '/springdoc-openapi-modules-securityorauthorizationserverwebmvc' & '/springdoc-openapi-modules-securityorauthorizationserverwebflux'
  * '/springdoc-openapi-modules-kotlin' &
  * '/springdoc-openapi-modules-hateoas' & '/springdoc-openapi-hateoas-service'