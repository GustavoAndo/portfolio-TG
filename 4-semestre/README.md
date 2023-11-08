# Em 2022-2 (4º Semestre)

## Sobre o Projeto

O cliente do projeto no quarto semestre foi a [2RP](https://2rpnet.com.br/), uma empresa que traz soluções e serviços personalizados para demandas na área de TI, atuando em qualquer segmento de mercado.

O objetivo do projeto deste semestre foi de desenvolver uma plataforma web para controlar a jornada de trabalho dos colaboradores da empresa em horas extras e sobreavisos.

A partir disso, como está sendo apresentado no GIF abaixo, a solução que foi implementada para o problema foi criar um um site com as seguintes funcionalidades:

* **Autenticação:** Inicialmente, temos a tela de autenticação de usuário que necessita do e-mail e senha para acessar o sistema;
* **Home:** Após se autenticar, o usuário estará na página Home com detalhes de seus últimos apontamentos e as horas trabalhadas, além de botões que redirecionam para páginas de apontar horas e visualizar esses apontamentos;
* **Cadastrar Horas:** Página com a funcionalidade principal do sistema. É um cadastro com 3 etapas para realizar o cadastro das horas extras e de sobreavisos trabalhadas por um colaborador;
* **Tabela de Apontamentos:** Nesta tela é possível visualizar os apontamentos de todos os colaboradores e, ao clicar no botão visualizar, é possível ter mais detalhes dos apontamentos e editá-los;
* **Usuários, Projetos, Clientes e Centros de Resultados:** Nestas páginas, temos a listagem, cadastro e edição de usuários, projetos, centros de resultados e clientes;
* **Manipulação de Verbas:** Similar com as páginas anteriores, nesta tela é possível visualizar, cadastrar e editar as verbas que serão utilizadas para o cálculo do valor de cada hora dos apontamentos;
* **Dashboards Individuais e Dashboards Gerais:** Nessas páginas, podemos visualizar dados anuais e mensais sobre os apontamentos de horas extras e de sobreavisos realizados durante este período. Nos Dashboards Individuais é apresentado dados do usuário autenticado e nos Dashboards Gerais é dado as informações gerais dos apontamentos de toda a empresa. Além disso é possível gerar um PDF com um resumo desses dados;
* **Histórico de Apontamentos:** Nesta tela, pode ser visualizado histórico de apontamentos do usuário que está utilizando o sistema;
* **Integração do Login:** Para maior facilidade de acessar a aplicação, foi implementada uma integração com o login da Google como opção de autenticação;
* **Nivelamento de Acesso:** Por fim, também implementamos três níveis de acesso de acordo com a pessoa autenticada, esses níveis são:
    * **Administrador:** Possui acesso completo da aplicação; 
    * **Gestor:** Possui o acesso completo da aplicação, com exceção da páginas de Usuários e Manipulação de Verbas;
    * **Colaborador:** Só tem permissão de acessar a página Home, Cadastrar Horas, Dashboards Individuais e Histórico de Apontamentos (ele pode editar o Apontamento, porém a aprovação ou reprovação só será feita pelo gestor ou administrador).

![Gif da execução do projeto](../img/4-semestre.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs-4/2RP)

## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **TypeScript:** linguagem de programação para a criação do site;
    - **React:** biblioteca para desenvolvimento de interfaces gráficas em páginas web.
* **Back-end:** 
    - **TypeScript:** linguagem de programação para contrução do back-end;
    - **NodeJS:** para execução de JavaScript fora de um navegador web;
    - **TypeORM:** ORM em TypeScript para criação da persistência de dados;
    - **PostgreSQL:** linguagem de programação para banco de dados para pesistência de dados.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto.

## Contribuições Pessoais

No quarto projeto, sendo desenvolvedor, colaborei com minha equipe principalmente na parte do back-end, utilizando NodeJS com TypeScript. Primeiramente, realizei a modelagem das entidades com TypeORM. Fiz a parte da persistência de dados e as operações de CRUD para os apontamentos de horas extras e de sobreavisos, além de também dar suporte para minha equipe na realização das mesmas funções para usuários, clientes, projetos e centro de resultados. Trabalhei um pouco no front-end em React com TypeScript para realização da tela de aprovação de apontamentos e auxiliei na criação da página de Dashboards com gráficos (com a biblioteca em React recharts) e geração de PDF's (com a biblioteca em JavaScript pdfJS). Além disso, implementei a autenticação no sistema, tanto no back-end (com a biblioteca jsonwebtoken) como no front-end (utilizando context do React) e também ajudei no nivelamento de acesso para os perfis diferentes no sistema. Por fim, o maior desafio foi a realização da integração do login com o Google OAuth 2.0, que foi uma grande novidade para mim.

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **TypeScript** - sei fazer com auxílio de consultas;
* **React** - sei fazer com auxílio de consultas;
* **NodeJS** - sei fazer com autonomia;
* **Typeorm** - sei fazer com autonomia;
* **MySQL:** - sei fazer com autonomia.

## Soft Skills

### Visão de Negócio

Com um projeto com bastante número de funcionalidades, foi importante ter uma visão de negócio para entender melhor cada uma delas e entender os requisitos do cliente.

### Colaboração

Como citado anteriormente, o grande número de requisitos e com uma equipe até que grande (8 integrantes) necessitou da minha colaboração com a equipe no desenvolvimento das atividades e na comunicação de quais tarefas já tinham sido feitas ou não.
