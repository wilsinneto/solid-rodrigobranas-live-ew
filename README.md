SOLID

5 princípios

1 - SRP

Single Responsibility Principle

Objetivo: Separar coisas que MUDAM POR OBJETIVOS DIFERENTES

Deve-se Mover responsabilidades

2 - OCP

Open/Closed Principle

Devemos estar fechados para modificação e abertos para extensão

3 - LSP

Liskov Substitution Principle

Se S (Beer, Whisky, Water) é subclasse de T (Item), em um programa deve ser possível substituir instâncias de T (Item) por instâncias de S (Beer, Whisky, Water), SEM QUEBRAR O FUNCIONAMENTO DO PROGRAMA

Pré-condições não podem ser fortalecidas

Deixando de aceitar ENTRADAS que a superclasse considera válida

Pós-condições não podem ser enfraquecidas

Deixando as saídas diferentes da expectativa de quem está chamando o método
Resumindo: Aceitando saídas mais AMPLAS

Invariantes devem se manter consistentes

Se uma subclasse permitir que o estado conceitual da hierarquia de classes fique inválido

4 - ISP

Interface Segregation Principle

Cuidado com interfaces MUITO ABRANGENTES, não obrigue subclasses a implementar métodos que elas não precisam

5 - DIP

Dependency Inversion Principle

High-level modules should not depend on low-level modules
Both should depend on abstraction
