# Desafio Desenvolvedor de Software Caronaê

Este repositório é destinado ao desafio técnico para os interessados em atuar na área de desenvolvimento do projeto, dando manutenção nos aplicativos, sites e APIs do projeto.

## Avisos

- Crie um repositório privado no GitHub e adicione o usuário `andradenathan` como colaborador.
- A implementação de cada sistema (front-end e back-end) poderá ser na linguagem e no framework (opcional) que o candidato preferir.
- Todo o processo de desenvolvimento, inclusive a forma de utilizar o Git (commits e maneira de resolução do problema) no repositório será avaliado.
- Ao finalizar o desafio, envie um e-mail para `caronae@dcc.ufrj.br` com o título "Entrega desafio técnico - desenvolvimento" com o link do repositório.

<br/>

# Avaliação

No Caronaê temos dois tipos de usuários: o motorista e o caronista. Os nomes são bem intuitivos, o motorista tem o poder de gerenciar caronas (criar, editar, excluir) e o caronista tem o poder de solicitar caronas. Um motorista também pode exercer o papel de caronista mas um caronista não pode exercer o papel de motorista visto que é necessário ter um carro para poder oferecer caronas.

## Back-end

O back-end deverá ter uma API RESTful que faça os seguintes métodos:

- Criar usuário
- Criar caronas
- Editar caronas
- Buscar caronas por parâmetros (data, partida e/ou destino) - isto é, pode ser possível pesquisar por todas as opções ou por apenas uma delas

Para as caronas, precisaremos ter informações do bairro de partida, o local de chegada, o caminho que será feito da partida até a chegada, a data e o horário de partida e de chegada e a quantidade de vagas disponível em um carro. 

Além disso, precisamos ter informações do carro do motorista, portanto, será necessário ser informado o modelo do veículo, a cor, a placa e o tipo de combustível (gasolina, gás, álcool, flex, diesel, elétrico, híbrido). Uma carona só pode ser criada se o usuário do tipo motorista tiver um carro cadastrado no sistema.

Para os dois tipos de usuários precisamos ter informações como o nome e sobrenome, e-mail, número de telefone, tipo de usuário e uma senha para acessar o sistema. 

**A implementação de uma autenticação é opcional.**

## Front-end

O front-end deverá consumir a API Rest e ter as seguintes funcionalidades:

- Página para cadastrar o usuário
- Página para exibir todas as caronas disponíveis
- Página para cadastrar uma carona
- Página para visualizar a carona criada

**A implementação do seu front-end poderá ser em um aplicativo ou website, a escolha é livre e isso não impactará na avaliação final.**


## Diferencial

- Documentação
- Propostas de melhorias ou sugestões
- Testes de integração
- Testes unitários
- Uso de Docker ou alguma outra ferramenta de containerização
- Uso de Design Patterns
- Uso de boas práticas de programação


## Materiais úteis

- [Design Patterns](https://refactoring.guru/design-patterns)
- [Containerize an application with Docker](https://docs.docker.com/get-started/02_our_app)
- [API Tutorial - Fetching data with Axios](https://www.youtube.com/watch?v=bMRrSqWFKqM)
- [How to build an API](https://www.mindk.com/blog/how-to-build-an-api/)