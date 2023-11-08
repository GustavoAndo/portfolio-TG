# Em 2023-2 (6º Semestre)

## Sobre o Projeto

Para o último projeto no sexto semestre, a empresa colaborativa foi a [Pro4Tech](https://www.pro4tech.com.br/), uma empresa que trabalha com soluções inovadoras que impulsionam o crescimento, otimizam processos e potencializa o negócio de seus clientes. Eles possuem serviços na área de desenvolvimento web, aplicativos, inteligência artificial (IA), inteligência empresarial (BI), automação de processos robóticos (RPA) e inteligência das coisas (IoT), utilizando métodos ágeis.

O projeto proposto pelo cliente foi de desenvolver uma aplicação para empresa com intuito de otimizar o processo de recrutamento e seleção de candidatos através de cadastros de vagas com uma descrição que demonstre um CHA (conhecimentos, habilidades e atitudes) indicado para ela. A partir desta descrição, será realizado um Web Scrapping para que se obtenha um ranqueamento de melhores candidatos com perfil mais aderente a vaga.

Assim, a partir da proposta e requisitos solicitados pela empresa, a solução implementada trouxe as seguintes funcionalidades ao sistema:

* **Autenticação:** A primeira tela apresentada é a de autenticação. Nela a empresa, antes de obter acesso a qualquer funcionalidade, deve enviar suas credenciais feitas através pelo e-mail e senha, além de uma autenticação de dois fatores;
* **Autenticação dois fatores:** Como citado anteriormente, a empresa deve realizar uma autenticação de dois fatores para acessar a aplicação, que é feito através de um e-mail que a empresa cadastrou; 
* **Cadastro de Empresa:** Caso a empresa ainda não tenha uma conta, é possível se cadastrar ao indicar que a mesma não possui conta na tela inicial. Após isso, o usuário será redirecionado para um formulário que deverá ser preenchido para fazer seu cadastro e a empresa conseguirá acessar o sistema;
* **Listagem das Vagas:** Ao entrar na aplicação, será exibido a listagem de vagas que foram cadastradas pela empresa. Nessa página, a empresa consegue editar as informações da vaga e visualizar o último ranqueamento de candidatos feito para vaga;
* **Ranqueamento de Candidatos:** Quando clicado no ícone de visualização, o usuário consegue visualizar os 8 melhores candidatos para aquela vaga e a porcentagem de match que cada um possui, ou seja, o quão apto para aquela vaga o candidato é; 
* **Cadastro da Vaga (CHA):** Nessa tela, o usuário pode cadastar uma vaga, colocando seu nome e nível, e a partir destes dois campos, uma IA gerará a descrição de vaga com base no CHA (conhecimentos, habilidades e atitudes) que podem ser posteriormente editados e aprimorados pela IA. Após isso, é possível salvar os dados da vaga novamente ou solicitar para fazer o match dos candidatos, que será realizado o Web Scrapping e selecionados os melhores perfis para vaga;
* **Perfil:** Também é possível a empresa visualizar suas informações cadastradas nesta página, além de editá-las e fazer a redefinição de senha;
* **Redefinição de senha:** Além de fazer a redefinição através da página de perfil citada anteriormente, é possível redefinir na tela de login, caso a pessoa tenha esquecido a sua senha;
* **Notificações:** Quando a empresa gera uma descrição CHA ou realiza um match, a empresa é notificada por e-mail. Além disso, é possível acessar uma página de notificações dentro do site.

![Gif da execução do projeto](../img/6-semestre.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs-6/Inodevs-doc)

## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **TypeScript:** linguagem de programação para desenvolvimento de interações da aplicação web;
    - **Vue.js:** framework em JavaScript para desenvolvimento de interfaces gráficas.
* **Back-end - Persistência de Dados:** 
    - **Java:** linguagem de programação para contrução do Back-End;
    - **Spring:** framework em Java para controle de dependência para fazer a persistência de dados;
    - **MySQL:** sistema de gerenciamento de banco de dados.
* **Back-end - Inteligência Artificial:** 
    - **Python:** linguagem de programação para contrução da inteligência artificial;
    - **Django:** framework em Python utilizado como servidor para acesso da inteligência artificial.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;
    - **Jira:** ferramenta para a gestão de projetos utilizando a metodologia Scrum.

## Contribuições Pessoais

Nesse último projeto, como Scrum Master, tive que aprender ainda mais sobre a metodologia ágil. Como contribuições, tive que desempenhar as funções da minha posição, trazendo a facilitação e agilidade nos tempos das reuniões da equipe (Por exemplo na Sprint Planning e Daily Scrum), a busca de mediação de conflitos, a transparência da equipe com relação a dificuldades e a avaliação do desempenho da equipe visualizando o gráfico de Burndown com a ferramenta Jira e a adaptação da equipe com base nas melhorias identificadas através da Sprint Retrospective. Além disso, também auxiliei um pouco no desenvolvimento com a criação do DDL do banco de dados MySQL, modelagem da entidade Vaga com Spring no back-end, implementação da integração da geração e aprimoramento de CHA com a API do ChatGPT em Python e na conexão do front-end (Vue.js) com o back-end (Spring) da tela de exibição do ranqueamento de candidatos.

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **TypeScript** - sei fazer com auxílio de consultas;
* **Vue.js** - sei fazer com auxílio de consultas;
* **Java** - sei fazer com autonomia;
* **Spring Boot** - sei fazer com autonomia;
* **Python** - sei fazer com autonomia;
* **Django:** - conhecimento básico.

## Soft Skills

### Empatia:

Como último semestre, haviam outras atividades além do projeto, como portifólio, tarefas da faculdade a serem finalizadas e ocupação com trabalho, desse modo, tive que ter empatia com meus colegas de equipe para entendê-los em situações difíceis para que fosse possível encontrar a melhor solução em conjunto para esses problemas.

### Liderança:

Por ter o papel de Scrum Master nesse semestre, fui comprometido com a melhoria contínua da equipe e do processo. Liderei na adoção de práticas ágeis mais eficazes e em ajustes nas ações da equipe conforme necessário.