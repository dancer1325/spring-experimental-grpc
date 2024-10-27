# Spring gRPC Docs

## README

* top level README & CONTRIBUTING guidelines documentation
  * generated -- via -- `mvn package` | sources this module
    * using
      * [`asciidoctor-reducer`](https://github.com/asciidoctor/asciidoctor-reducer) 
      * [`downdoc`](https://github.com/opendevise/downdoc)

## Configuration Properties

1. `org.springframework.grpc.internal.ConfigurationPropertiesAsciidocGenerator` 
   1. == ".java" / when the module is built -> it's compiled 
   2. when Maven `package` phase is run -> generate an asciidoc page / 
      1. contain each of the configuration properties
      2. included | Antora reference documentation

## Antora Site

* | project root directory
    ```
    ./mvnw -pl spring-grpc-docs antora
    ```
  * view the output | `spring-grpc-docs/target/antora/site/index.html` 
