# O que nós buscamos

* Responsável por desenvolver, testar e documentar rotinas;
* Atuar em implementações, melhorias de performance e integrações; 
* Desenvolver códigos bem estruturados utilizando boas práticas de programação;
* Realizar revisão por pares dos artefatos de programação; 
* Interagir com todo o time Scrum de forma construtiva na busca por resultados que agreguem valor aos clientes; 
* Construir código com testes automatizados/unitários para garantir a qualidade.

# Requisitos e diferenciais das vagas

## Requisitos:

* PHP 7+;
* Laravel 5+;
* Bom domínio de testes unitários/integração usando o PhpUnit;
* MySQL;
* Rest APIs;
* Conhecimento básico em modelagem de banco de dados;
* Noções básicas de scrum e metodologias ágeis;
* Dominio do Git para versionamento de projetos;
* Experiência na utilização do docker;

## Diferenciais:

* NodeJs;
* Golang
* Microservices;
* Experiência na utilização de banco de dados não relacionais;
* Experiência em tecnologias de IA ou machine learning;
* Linux;
* AWS;

# Teste

Considerando os dados disponíveis na URL -> https://raw.githubusercontent.com/citartech/job-vacancies/master/assets/country-codes.txt

Escreva uma aplicação com um código bem estruturado, orientado a objetos e utilizando, sempre que possível e adequado, padrões de projetos como MVC por exemplo. Busque criar uma aplicação que possibilite e facilite a implementação de testes unitários, melhor ainda seria se já viesse com alguns testes de unidade e integração e seguindo princípios como KISS e SOLID.

Objetivos:

* Criar uma pagina simples com três botões: 
  1. Um que direcione para uma segunda página com a listagem formatada dos Países; 
  2. Um segundo que baixe um arquivo CSV com os dados; 
  3. Um terceiro que baixe uma planilha de excel com os dados;
* Todas as saidas, em tela ou em arquivo, devem ser ordenados pelo nome do país em ordem inversa;
* Em todas as saídas além dos dois campos adicione um terceiro com a composição "(BR) BRASIL"
* Em todas as chamadas faça o processamento dos dados usando a URL passada como fonte de dados e sempre pelo backend, a cada nova solicitação;
* Use um cache em arquivo para persistir a informação recuperada da URL, mas o use apenas se a consulta principal falhar;

Use o git para o versionamento do projeto e suba em um repositório publico do github.

Faça uma breve documentação do processo para rodar a aplicação e testar seu funcionamento no arquivo README.md do repositório.

Após o término, enviar o link do repositório para o e-mail rh.dev@grupocitar.com.br
