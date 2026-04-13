# aula1

### Diagrama caso de uso
teste

```mermaid
graph LR
    subgraph "GEEAR ONG"
        1((Criar conta usuário))
        2((Login))
        3((Visualizar ONGs))
        4((Fazer doação))
        5((Voluntariar))
        6((Editar perfil))
        7((Fazer denúncia))
        8((Visualizar histórico de doações))

        9((Criar conta ONG))
        10((Editar perfil))
        11((Visualizar doações recebidas))
        12((Visualizar candidatos a voluntário))


    end

    usu((Usuário)) --- 1
    usu --- 2
    usu --- 3
    usu --- 4
    usu --- 5
    usu --- 6
    usu --- 7
    usu --- 8


    ong((ONG)) --- 9
    ong --- 2
    ong --- 10
    ong --- 11
    ong --- 12 
