# Spring Cloud Azure

[Spring Cloud](http://projects.spring.io/spring-cloud/) provides boilerplate patterns for developers to quickly build and orchestrate their microservice based applications. Based on that, **Spring Cloud Azure** is designed to provide seamless Spring integration with Azure services. 

Developers can adopt a Spring-idiomatic way to automatically provision resources and take advantage of services on Azure, with only few lines of configuration and minimal code changes. It takes care of configurations and offers key features to interact with Azure services, such as Azure Storage and Azure Event Hub. 

## Module and Starter 

Module | Spring Library | Description
---|---|---
[Spring Cloud Stream Binder for Azure Event Hub](spring-cloud-azure-eventhub-stream-binder/) | [Spring Cloud Stream](https://cloud.spring.io/spring-cloud-stream/) | Binding implementation for Spring Cloud Stream with Azure Event Hub service
[Spring Cloud Stream with Azure Event Hub Kafka API](spring-cloud-azure-samples/spring-cloud-stream-eventhub-kafka-sample/) | [Spring Cloud Stream](https://cloud.spring.io/spring-cloud-stream/) | Binding implementation for Spring Cloud Stream with Azure Event Hub service KafKa API 
[Spring Resource Abstraction for Azure Storage](spring-cloud-azure-storage/) | [Spring Resource](https://docs.spring.io/spring/docs/current/spring-framework-reference/core.html#resources) | Implementation for Spring Resource with Azure Blob Storage
[Spring Caching with Azure Redis Cache](spring-cloud-azure-samples/spring-cloud-azure-cache-sample) | [Spring Caching](https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-caching.html) | Implementation for Spring Caching with Azure Redis Cache

The following Spring Boot Starters are available in Maven Central Repository. 

Starter Name | Version | Sample
---|---|---
[spring-cloud-azure-starter-eventhub](spring-cloud-azure-starters/spring-cloud-azure-starter-eventhub/) | [![Maven Central](https://img.shields.io/maven-central/v/com.microsoft.azure/spring-cloud-azure-starter-eventhub.svg)](https://search.maven.org/#search%7Cga%7C1%7Ca%3A%22spring-cloud-azure-starter-eventhub%22) | [Sample](spring-cloud-azure-samples/spring-cloud-azure-eventhub-binder-sample)
[spring-azure-starter-storage](spring-cloud-azure-starters/spring-azure-starter-storage/) | [![Maven Central](https://img.shields.io/maven-central/v/com.microsoft.azure/spring-azure-starter-storage.svg)](https://search.maven.org/#search%7Cga%7C1%7Ca%3A%22spring-azure-starter-storage%22) | [Sample](spring-cloud-azure-samples/spring-cloud-azure-storage-sample)
[spring-azure-starter-cache](spring-cloud-azure-starters/spring-azure-starter-cache/) | [![Maven Central](https://img.shields.io/maven-central/v/com.microsoft.azure/spring-azure-starter-cache.svg)](https://search.maven.org/#search%7Cga%7C1%7Ca%3A%22spring-azure-starter-cache%22) | [Sample](spring-cloud-azure-samples/spring-cloud-azure-cache-sample)

## Sample and Tutorial 

Please use the [samples](spring-cloud-azure-samples/) as a reference for how to use Spring Cloud Azure in your projects. For more information about building Spring applications on Azure, please check [Spring on Azure tutorials](https://docs.microsoft.com/en-us/java/azure/spring-framework/?view=azure-java-stable). 

You can also visit [Spring Cloud Azure Playground](https://aka.ms/springcloud) to quickly generate a new Spring Cloud applications for Azure.  

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

## Code of Conduct 

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Data and Telemetry 

This project collects usage data and sends it to Microsoft to help improve our products and services. Read our [privacy statement](https://privacy.microsoft.com/en-us/privacystatement) to learn more. 

To disable this, you can add `spring.cloud.azure.telemetry.enabled=false` in the `application.properties` file. 
