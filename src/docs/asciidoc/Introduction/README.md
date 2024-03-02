# Introduction
* := JAVA library which
  * allows
    * in Spring Boot projects -> automating the generation of API documentation
      * in format
        * JSON   -- '/v3/api-docs' --
        * YAML   -- '/v3/api-docs.yaml' --
        * HTML   -- '/swagger-ui/index.html' --
      * based on
        * spring configurations     -- check '../Properties'--
        * class structure 
        * various annotations
          * swagger-api
  * requirements
    * application at runtime
  * maintained by the community
  * supports
    * OpenAPI 3
    * Spring-boot v3 (Java 17 & Jakarta EE 9)
    * JSR-303, specifically for @NotNull, @Min, @Max, and @Size.
    * Swagger-ui
    * OAuth 2
    * GraalVM native images

# Note:
* Check 'spring-openapi-demos' repo, under the project 
  * '/springdoc-openapi-book-service' &
  * '/springdoc-openapi-book-service-v3'
  * '/springdoc-openapi-oauth2'
  * '/springdoc-openapi-book-service-graalvm'
