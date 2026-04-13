# aula1

### Diagrama caso de uso
teste

```mermaid
graph LR
    subgraph "Online Store"
        UC1((View Items))
        UC2((Place Order))
        UC3((Process Payment))
    end

    Customer((Customer)) --- UC1
    Customer --- UC2
    Admin((Admin)) --- UC3

    UC2 -.->|include| UC1

