# Features

## Additional information
* `@OpenAPIDefinition`
  * Swagger-Core
  * API information
* `@SecurityScheme`
  * Swagger-Core
  * Security documentation

## Add error handling with @ControllerAdvice to the documentation
* requirements
  * ALL methods use `@ResponseStatus`

# Disable documentation
* `springdoc.api-docs.enabled=false`
  * disable the JSON / YAML documentation generated -- provided by springDoc --
    * -> also disabled HTML documentation
* `springdoc.swagger-ui.enabled=false`
  * disable the HTML documentation generated        -- provided by Swagger-UI --

# Swagger UI configuration
* `springdoc.swagger-ui.OffitialSwaggerUIProperties`
  * [OffitialSwaggerUIProperties](https://swagger.io/docs/open-source-tools/swagger-ui/usage/configuration/)

# Note:
* Check 'spring-openapi-demos' repo, under the project 
  * '/springdoc-openapi-microservices' & '/springdoc-openapi-oauth2'
  * '/springdoc-openapi-person-service' & '/springdoc-openapi-spring-boot-1' & 
  * '/springdoc-openapi-features' &