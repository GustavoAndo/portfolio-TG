# Em 2021-2 (2º Semestre)

## Sobre o Projeto

Neste segundo projeto, foi o primeiro com uma empresa parceira, a [JetSoft](https://www.jetsoft.com.br/), uma empresa de software que oferece serviços e produtos a outros clientes.

O objetivo do projeto foi de criar um CRUD (Create, Read, Update e Delete) para essa empresa de software com intuito de emitir relatórios mensais de controle de presença de colaboradores com alocação específica de diferentes postos de trabalhos acordados em um contrato com o seu respectivo cliente.

Assim como está sendo mostrado no GIF abaixo, a partir do problema, foi criado um aplicativo web para solucioná-lo. E nele foi implementado as seguintes funcionalidades:

* **Marcação de presença:** Com o colaborador autenticado pelo sistema, na tela inicial, é possível marcar a presença no dia letivo de trabalho;
* **Autenticação e nivelamento de acesso:** Ao entrar no site, será necessário o login e senha do usuário para acessar as funcionalidades do sistema. Além disso, dependendo do nível de acesso, será permitido apenas acessar algumas páginas da aplicação. Desse modo, os níveis de acesso e suas permissões são:
    - **Nível Operacional:** Nesse nível mais baixo, só é permitido entrar na páginas Home (para marcar a própria presença) e na página com mais informações dos desenvolvedores;
    - **Nível Tático:** Esse é o nível mais alto do sistema. Com esse perfil é possível acessar todas as páginas e realizar todas as funcionalidades do site.
* **Controle de Perfis:** Nesta página, é possível ver os 6 cadastros implementados para solução do problema, sendo eles: Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários. E, ao serem clicados, o usuário é redirecionado para um formulário para inserir os campos necessários e cadastrá-los no sistema;
* **Quadro de Presença:** A página principal com o quadro de presenças. Nele contém as presenças dos postos de trabalho e também as presenças de cada colaborador do seu respectivo posto que são possíveis de serem editados e excluídos. Nesta tela, também é permitido realizar pesquisas com o nome do colabodor ou posto e existe a funcionalidade de gerar relatório do quadro de presença (com uma cópia do quadro e com dados de frequência de presença) e relatório gerencial (com gráficos, dados e porcentagens relacionados a frequência de colaboradores e postos), que podem ser exportados como pdf ou salvos dentro de um histórico na aplicação;
* **Edições:** Tela com tabelas de Colaboradores, Contratos, Clientes, Postos de Trabalho, Alocações e Usuários e seus respectivos dados. Nesta página é possível a visualização, edição e exclusão destes dados;
* **Página dos Desenvolvedores:** Informações sobre os desenvolvedores do sistema;
* **Guias:** Além das páginas do sistema, foram implementados os seguintes PDF's:
    - **Guia de Instalação:** Com instruções de como executar a aplicação em localhost;
    - **Guia de Usuário:**: Para auxiliar os usuários a utilizar o sistema;
    - **Contenção de Problemas:** Soluções de erros que podem ocorrer na aplicação.

![Gif da execução do projeto](../img/2-semestre.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/Inodevs/Inodevs)
## Tecnologias Utilizadas

* **Front-end:** 
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **JavaScript:** linguagem de programação para criar as interações do site.
* **Back-end:** 
    - **PHP:** linguagem de programação que foi utilizado para fazer as operações de CRUD dos dados no banco;
    - **MySQL:** linguagem de programação para banco de dados para pesistência de dados do cadastros.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;

## Contribuições Pessoais

No segundo semestre, também tive o papel de desenvolvedor. Colaborei com minha equipe principalmente com a tecnologia PHP e MySQL, onde eu trabalhei com a criação de um CRUD (Create, Read, Update e Delete) para o quadro de presença e nos cadastros do controle de perfis. Ainda com PHP, fiz a mecânica de autenticação e auxiliei no nivelamento de acesso dos usuários. Além disso, ajudei a criar e estilizar as páginas de quadro de presença e de edições com HTML5 e CSS3. Em JavaScript, fiz a funcionalidade de busca do quadro de presenças e o relógio na página incial. Por fim, um dos maiores desafios, foi trabalhar com os relatórios, com a manipulação de dados (cálculos e lógica relaizada em PHP), geração de gráficos (com JavaScript e Google Charts) e para a geração dos PDF's destes relatórios (com DOMPDF em PHP).

## Hard Skills

* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **JavaScript** - sei fazer com auxílio de consultas;
* **PHP** - sei fazer com autonomia;
* **MySQL:** - sei fazer com autonomia.

## Soft Skills

### Proatividade

Com diversas funcionalidades novas e complexas solicitadas pelo cliente, como por exemplo a geração de relatórios com gráficos e pdf, tive bastante proatividade para selecioná-las para serem realizadas, assim, pesquisando e pensando na lógica de como seriam concluídas.

### Entrega de Resultados

Como citado anteriormente, junto com a proatividade de selecionar as atividades complexas, realizei bastante atividades com bons resultados e consegui entregá-las de forma eficiente e agilmente.