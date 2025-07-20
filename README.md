# DDD (Domain-driven Design) and Clean Code

Design dirigido à domínio

## Domínio

O domínio é o assunto ou a área de interesse do software. É o contexto em que o software opera e as regras que governam esse contexto.

- Domain Experts
  - Conversar com especialistas do domínio é essencial para entender as regras e necessidades do negócio.

- Linguagem Ubíqua
  - Uma linguagem comum entre desenvolvedores e especialistas do domínio ajuda a evitar mal-entendidos e garante que todos estejam na mesma página.

- Usuário
  - Cliente
  - Fornecedor
  - Atendente
  - Barman

- Agregados
- Value Objects
- Eventos de Domínio
- Subdomínios (Bounded Contexts)
- Entidades
- Casos de Uso

## Conceitos de Patterns (Padrões)

- Aggregate
  - Duas ou mais entidades que são tratadas como uma única unidade de dados.
- WatchedList
  - Uma lista de entidades que são monitoradas para mudanças.

## Exemplo

- Order -> OrderItem[]
- Order -> Shipping

- Question -> Attachment

### Criação

- Título
- Conteúdo
- Anexos (3)

### Edição

- Título
- Conteúdo

- Adicionar um novo anexo (create)
- Remover o segundo anexo que tinha sido criado previamente (delete)
- Editar um anexo existente (update)
