# Unofficial-Elevenlabs-OpenAPI definition
A unofficial OpenAPI definition of the Elevenlabs API for use with codegen tools.
The API is property of [Elevenlabs Inc.](https://beta.elevenlabs.io) and their [Terms of Service](https://beta.elevenlabs.io/terms) apply.

## How to use
To generate a client for a specific language you can use [openapi-generator-cli](https://central.sonatype.com/artifact/org.openapitools/openapi-generator-cli/6.5.0/overview).
>java -jar openapi-generator-cli-6.5.0.jar generate -i elevenlabs.yaml -g \<generator\> -o \<output-directory\>

For a full list of available generators:
>java -jar openapi-generator-cli-6.5.0.jar list
### Examples
- To generate a pyhton client which utilizes the FastAPI:
>java -jar openapi-generator-cli-6.5.0.jar generate -i elevenlabs.yaml -g python-fastapi -o python-fastapi-client
- To generate a java client:
>java -jar openapi-generator-cli-6.5.0.jar generate -i elevenlabs.yaml -g java -o java-client
