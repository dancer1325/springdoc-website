# Getting started
* Unique required change 
```
<dependency>
  <groupId>org.springdoc</groupId>
  <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
  <version>2.3.0</version>
</dependency>
```
* What does it make?
  * Spring Boot — is integrated with — [Swagger UI](https://github.com/swagger-api/swagger-ui)
  * Swagger UI
    * http://server:port/context-path/swagger-ui.html -- HTML format --
    * If you customize `springdoc.swagger-ui.path=/CustomPath.html` → 
      * http://server:port/context-path/CustomPath.html
        * redirect to the default one!!!
      * http://server:port/context-path/swagger-ui/index.html
        * still valid!!!
  * OpenAPI
    * Default
      * http://server:port/context-path/v3/api-docs  -- JSON format --
      * http://server:port/context-path/v3/api-docs.yaml  -- YAML format --
    * If you customize `springdoc.api-docs.path=/CustomPath` → 
      * JSON
        * http://server:port/context-path/CustomPath
        * http://server:port/context-path/v3/api-docs
          * NOT valid!!
      * YAML
        * http://server:port/context-path/CustomPath.yaml
        * http://server:port/context-path/v3/api-docs.yaml
          * NOT valid!!

# Note:
* Check 'spring-openapi-demos' repo, under the project 
  * '/springdoc-openapi-book-service'
  * '/springdoc-openapi-book-service-customized'
