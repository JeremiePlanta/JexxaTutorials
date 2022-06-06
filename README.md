[![Maven Test Build](https://github.com/jexxa-projects/JexxaTutorials/actions/workflows/mavenBuild.yml/badge.svg)](https://github.com/jexxa-projects/JexxaTutorials/actions/workflows/mavenBuild.yml)

# Tutorials 

## General notes

All tutorials focus on the usage of Jexxa. Therefore, the business logic in these tutorials is without any special 
meaning. In addition, we assume that you have a basic understanding of: 
* Writing Java code and build your programs using maven.

* A general understanding of the used technology stacks such as a messaging system or a database.

* A general understanding of [ports and adapters](https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/).

* All tutorials run by default without any additional infrastructure services such as JMS or a database.

* In case you want to just run the tutorials, you can use: 
  * Docker images provided [here](https://github.com/jexxa-projects?tab=packages&repo_name=JexxaTutorials). Please note that you need a running ActiveMQ and Postgres database   
  * [Docker stack](deploy/docker-compose.yml) starting all tutorials 
  
## HelloJexxa
See documentation [HelloJexxa](HelloJexxa/README.md)

## TimeService - Async Messaging
See documentation [TimeService](TimeService/README.md)

## TimeService - Flow of Control
See documentation [TimeService - Flow of Control](TimeService/README-FlowOfControl.md)

## BookStore - Using a Repository  
See documentation [BookStore](BookStore/README.md)

## BookStore - Writing Tests 
See documentation [BookStore](BookStore/README-JexxaTest)

## BookStoreJ - Pattern Language 
See documentation [BookStore - Pattern language](BookStore/README-PatternLanguage.md)

## BookStoreJ - OpenAPI Support 
See documentation [BookStore - With OpenAPI support](BookStore/README-OPENAPI.md)

## ContractManagement - Using an ObjectStore  
See documentation [ContractManagement](ContractManagement/README.md)


