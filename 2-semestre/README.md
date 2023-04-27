# Em 2021-2 (2º Semestre)

## Sobre o Projeto

Neste segundo projeto, foi o primeiro projeto com uma empresa parceira, que foi a JetSoft, uma empresa de software que oferece serviços e produtos a outros clientes.

O objetivo do projeto foi de criar um CRUD para essa empresa de software para emissão de relatórios mensais de controle de presença de colaboradores com alocação específica em postos de trabalhos acordados em um contrato com o seu cliente.

Assim como está sendo mostrado no GIF abaixo, a partir do problema, foi criado um aplicativo web para solucioná-lo. E nele foi implementado as seguintes funcionalidades:

* **Marcação de presença:** Com o colaborador autenticado pelo sistema, na tela inicial, é possível marcar a presença no dia letivo de trabalho;
* **Autenticação e nivelamento de acesso:** Ao entrar no site, será necessário o login e senha do usuário para acessar as funcionalidades do sistema. Além disso, dependendo do nível de acesso, será permitido apenas acessar algumas páginas da aplicação. Desse modo, os níveis de acesso e suas permissões são:
    - **Nível Operacional:** Nesse nível mais baixo, só é permitido marcar entrar nas páginas Home (para marcar a própria presença) e a página dos desenvolvedores;
    - **Nível Tático:** Esse é o nível mais alto do sistema. Além das funcionalidades já citadas do nível operacional, com esse nível é possível fazer todas acessar todas as páginas e realizar todas as utilidades do site.
* **Controle de Perfis:** Nesta página, é possível ver os 6 cadastros implementados para solução do problema, sendo eles: Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários. E ao serem clicados, o usuário é redirecionado para um formulário para inserir os campos necessários e cadastrá-los no sistema;
* **Quadro de Presença:** A página principal com o quadro de presenças. Nele contém as presenças dos postos de trabalho e também as presenças de cada colaborador do seu respectivo posto que são possíveis de serem também editados e excluídos. Nesta tela, também tem como pesquisar e gerar relatórios do quadro de presença e gerencial (com gráficos, dados e porcentagens relacionados a frequência de frequência dos postos e colaboradores), que podem ser exportados como pdf ou salvos dentro de um histórico na aplicação;
* **Edições:** Tela com tabelas de Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários e seus respectivos dados. Nesta página é possível a visualização, edição e exclusão destes dados;
* **Página dos Desenvolvedores:** Informações sobre os desenvolvedores do sistema;
* **Guias:** Além das páginas do sistema, foram implementados os seguintes PDF's:
    - **Guia de Instalação:** Com instruções de como executar a aplicação em localhost;
    - **Guia de Usuário:**: Para auxiliar os usuários a utilizar o sistema;
    - **Contenção de Problemas:**  Soluções de erros que podem ocorrer na aplicação.

![Gif da execução do projeto](../img/2-semestre.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs/Inodevs)
## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **JavaScript:** linguagem de programação para criar as interações do site.
* **Back-end:** 
    - **PHP:** linguagem de programação que foi utilizado para armazenar e consultar dados no banco;
    - **MySQL:** linguagem de programação para banco de dados para pesistência de dados do cadastros.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;

## Contribuições Pessoais

No segundo semestre, também tive o papel de desenvolvedor. Colaborei com minha equipe principalmente com a tecnologia PHP e MySQL, onde eu trabalhei com a criação de um CRUD (Create, Read, Update e Delete) para o quadro de presença e de alguns cadastros. Ainda com PHP, fiz a mecânica de autenticação e auxiliei no nivelamento de acesso dos usuários. Além disso, ajudei a criar e estilizar as páginas de quadro de presença e de edições de cadastros com HTML5 e CSS3. Em JavaScript, fiz a funcionalidade de busca do quadro de presenças e o relógio na página incial. Por fim, um dos maiores desafios, foi trabalhar com os relatórios, com a manipulação de dados (cálculos em PHP), geração de gráficos (com JavaScript e Google Charts) e para a geração do PDF (com DOMPDF em PHP).

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **JavaScript** - sei fazer com auxílio de consultas;
* **PHP** - sei fazer com autonomia;
* **MySQL:** - sei fazer com autonomia;

## Soft Skills

* **Proatividade:** para criar funcionalidades díficeis, como de quadro de presença e relatórios, fui bem proativo para pesquisar as tecnologias e pensar na lógica de como as atividades seriam concluídas;
* **Entregas de Resultados:** consegui me desenvolver para entregar todas as atividades de forma que fosse satisfatório para equipe e que atendessem aos requisitos do cliente;
* **Planejamento:** ainda em ensino remoto, o planejamento foi de extrema importante para concluir as tarefas.
