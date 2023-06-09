# Em 2022-2 (4º Semestre)

## Sobre o Projeto

O cliente do projeto no quarto semestre foi a 2RP, uma empresa de que traz soluções e serviços personalizados para demandas na área de TI, atuando em qualquer segmento de mercado.

O objetivo do projeto deste semestre foi de desenvolver uma plataforma web para controlar a jornada de trabalho dos colaboradores da empresa em horas extras e sobreavisos.

A partir disso, como está sendo apresentado no GIF abaixo, a solução que foi implementada para o problema foi criar um um site com as seguintes funcionalidades:

* **Autenticação:** Inicialmente, temos a tela de autenticação de usuário que necesita do email e senha para acessar o sistema;
* **Página Home:** Após se autenticar, o usuário estará na página Home com detalhes de seus últimos apontamentos e as horas trabalhadas e botões para redirecionar para páginas de apontar horas e visualizar esses apontamentos;
* **Apontamento de Horas:** Página com a funcionalidade principal do sistema. É um cadastro com 3 etapas para realizar o cadastro das horas extras e de sobreavisos trabalhadas por um colaborador;
* **Tabela de Apontamentos:** Nesta tela é possível visualizar os apontamentos de todos os colaboradores;
* **Edição de Apontamentos:** Ao clicar no botão visualizar de algum apontamento, será possível editar o apontamentos
* **Página de Usuários, Projetos, Clientes e Centro de Resultados:** Nestas páginas, temos a listagem, cadastro e edição de usuários, projetos, centros de resultados e clientes;
* **Manipulação de Verbas:** Parecido com as páginas anteriores, nesta tela é possível visualizar, cadastrar e editar as verbas que serão utilizadas para o cálculo do valor de cada hora dos apontamentos;
* **Dashboards e Dashboard Geral:** Nessas páginas, podemos visualizar dados anuais e mensais sobre os apontamentos de horas extras e de sobreaviso realizados durante este período. Nos Dashboards possuímos dados do usuário autenticado e nos Dashboards Gerais possuímos informações gerais dos apontamentos de toda a empresa. Além disso é possível gerar um pdf com um resumo destes dados;
* **Histórico de Apontamentos:** Nesta tela, pode ser visualizado histórico de apontamentos do usuário que está utilizando o sistema;
* **Integração do Login:** Para maior facilidade de acessar a aplicação, foi implementada uma integração com o login da Google como opção de autenticação;
* **Nivelamento de Acesso:** Por fim, também implementamos três níveis de acesso de acordo com a pessoa autenticadas, esses níveis são:
    * **Administrador:** Possui acesso completo da aplicação; 
    * **Gestor:** 
    * **Colaborador:** 

![Gif da execução do projeto](../img/4-semestre.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs-4/2RP)

## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **TypeScript:** linguagem de programação para criar as interações do site;
    - **React:** biblioteca para desenvolvimento de interfaces gráficas em páginas web.
* **Back-end:** 
    - **TypeScript:** linguagem de programação para contrução do Back-end;
    - **NodeJS:** para execução de JavaScript fora de um navegador web;
    - **TypeORM:** ORM em TypeScript para criação da persistência de dados;
    - **MySQL:** linguagem de programação para banco de dados para pesistência de dados do cadastros.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;

## Contribuições Pessoais

No quarto projeto, sendo desenvolvedor, colaborei com minha equipe principalmente na parte do Back-End, utilizando NodeJS com TypeScript. Primeiramente, realizei a modelagem das entidades com a ORM TypeORM. Fiz a parte da persistência de dados e as operações de CRUD para os apontamentos de horas extras e de sobreavisos, além de também dar suporte para minha equipe na realização das mesmas funções para usuários, clientes, projetos e centro de resultados. Trabalhei um pouco no Front-end em React com TypeScript para realização da tela de aprovação de apontamentos e auxiliei na criação da página de Dashboards e geração de pdf's. Além disso, implementei a autenticação no sistema, tanto no Back-end (com a biblioteca jsonwebtoken) como no Front-end (utilizando context do React) e também ajudei no nivelamento de acesso. Por fim, o maior desafio foi a realização da integração do login com o Google OAuth 2.0, que foi uma grande novidade para mim.

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **TypeScript** - sei fazer com auxílio de consultas;
* **React** - sei fazer com auxílio de consultas;
* **NodeJS** - sei fazer com autonomia;
* **Typeorm** - sei fazer com autonomia;
* **MySQL:** - sei fazer com autonomia;

## Soft Skills

* **Comunicação:** com uma equipe com 8 integrantes, uma boa comunicação para todos se interarem com o andamento do projeto foi essencial para a entrega das sprints;
* **Proatividade:** para trabalhar com duas linguagens, tanto no front-end e back-end, foi necessário proatividade para aprender as linguagens e realizar as tarefas com sucesso;
* **Organização:**  com maior número de pessoas no time, a organização das atividades foi imporante para entregar tudo o que foi proposto para as sprints.
