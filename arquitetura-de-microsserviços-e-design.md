# 📌 Arquitetura de Microsserviços e Design

## 🔹 O que é importante

### 📌 Princípios Essenciais
- **Desacoplamento:** Cada microsserviço deve ser independente, com responsabilidades bem definidas (**SRP - Single Responsibility Principle**).
- **Escolher a arquitetura correta:** Hexagonal, Clean Architecture ou Layered.
- **Bounded Contexts:** Defina limites claros para cada microsserviço.
- **API Gateway:** Use um API Gateway para gerenciar requisições e roteá-las para os microsserviços corretos.

### 🏛️ Padrões Arquiteturais
- **REST, Event-Driven, CQRS (se necessário), DDD (se aplicável).**
- **Padrões de desenvolvimento:** SOLID, DRY, KISS, YAGNI.
- **Estratégia de separação de serviços:** Monólito Modular, Event-Driven, API-First.
- **Identificação de dependências entre serviços.**

## 🔹 Soluções em Java

### 🛠️ Frameworks e Ferramentas
- **Spring Cloud Gateway:** Para implementar um API Gateway.
- **Spring Boot:** Para criar microsserviços de forma rápida e eficiente.
- **Quarkus e Micronaut:** Alternativas ao Spring Boot para microsserviços leves e rápidos.

### 🏗️ Arquitetura de Microsserviços
- **Resiliência:** Implementação com Hystrix/Resilience4j e Circuit Breaker.
- **Sidecar Pattern:** Service Mesh com Istio.
- **Event-Driven Architecture:** Mensageria com Kafka, RabbitMQ.
- **Saga Pattern:** Gerenciamento de transações distribuídas.
- **API Gateway:** Implementação com Spring Cloud Gateway.
- **Service Discovery:** Uso de Eureka ou Consul.
