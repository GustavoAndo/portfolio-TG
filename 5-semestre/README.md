# Em 2023-1 (5º Semestre)

## Sobre o Projeto

A empresa parceira deste projeto foi a [IACIT](https://www.iacit.com.br/), uma empresa que atua no desenvolvimento de produtos e sistemas aplicados às áreas de auxílio do controle e do tráfego aéreo e marítimo, defesa e segurança pública, fábrica de software, meteorologia, telemetria e agronegócio e pesquisa, desenvolvimento e inovação.

O cliente propôs para o quinto semestre o desenvolvimento de uma aplicação híbrida que funcione como Serviço de Atendimento ao Cliente (SAC), onde o usuário poderá cadastrar registros de ocorrências (RO's) e o suporte conseguirá verificar as solicitações criadas e solucionar os problemas do usuário, podendo também entrar em contato via chat.

Sendo assim, a solução que implementamos foi o desenvolvimento de uma aplicação mobile e web, que pode ser visto sua execução no primeiro e segundo GIF abaixo respectivamente. Portanto, as funções implementadas foram:

* **Autenticação:** Para acessar a aplicação, primeiramente, é necessário se autenticar no sistema com e-mail e senha;
* **Nivelamento de Acesso:** Existem dois níveis de acesso:
    * **Cliente:** Usuários que criam os RO's e aguardam serem resolvidas. Ele tem as seguintes permissões: acessar a página Home; criar, fechar e acompanhar os RO's; e entrar em contato com o suporte via chat;
    * **Administrador:** Encaminhado para resolver os RO's. Possui acesso completo da aplicação;
* **Home:** Após se autenticar, o usuário possui várias opções de botões para acessar as funcionalidades do sistema (apenas na versão mobile, na versão web o usuário é redirecionado para página Registro de Ocorrência, já que temos um menu de navegação maior);
* **Registro de Ocorrência:** Nesta página, contém a listagem de registros de ocorrências, que podem ser buscados por ID ou título e, caso o usuário seja um administrador, pode ser filtrado por Minhas Tasks, onde é mostrado apenas ROs indicados para o usuário resolver. Além disso, ao clicar em um RO específico, o administrador consegue atualizá-lo com uma solução para o problema. Após esta resposta, o cliente poderá analisar e concluir ou recusar o RO. Caso seja a primeira opção, o RO é fechado, caso contrário, ele deverá ser analisado novamente pelo administrador; 
* **Membros do Suporte:** Tela com a listagem dos usuários cadastrados no sistema. Ao clicar em um usuário específico, será mostrado mais detalhes dele e seus dados poderão ser atualizados;
* **Novo Registro de Ocorrência:** Nesta tela é possível cadastrar um novo Registro de Ocorrência;
* **Cadastrar Novo Usuário:** Página para a criação de um novo usuário para entrar na aplicação;
* **Redefnição de Senha:** Quando um usuário é criado pelo administrador, o usuário receberá um e-mail com um link de redefinição de senha, que será redirecionado a uma página da aplicação para que ele possa definir sua senha. Além disso, também é possível clicar em "Esqueci a senha" para receber um e-mail para a redefinição;
* **Meus Chats:** Página que é possível conversar diretamente com o responsável da resolução dos RO's; 
* **Opções Extras:** Tela com opções extras de segurança. É possível, caso o usuário seja um administrador, criar um backup e restaurar o último backup, além de disponibilizar, independetemente de ser administrador, os termos de compromisso na utilização da aplicação;
* **Relatório:** Nesta página temos um gráfico com os dados dos RO's que foram abertos, além de especificar quantos estão sem tratamento, em tratamento e concluídos. É possível filtrar os dados do dashboard pro mês e usuário;
* **Notificações:** Nesta tela, é possível visualizar as notificações que aparecem para caso um RO seja criado, atualizado, recusado ou concluído. Além disso, caso o usuário queira, ele pode receber e-mails dessas notificações;
* **Perfil:** Página com as informações do usuário.

![Gif da execução do projeto](../img/5-semestre-app.gif)

![Gif da execução do projeto](../img/5-semestre-web.gif)

> [Acesse o repositório no GitHub clicando aqui](https://github.com/inodevs-5/Reportify_Doc)

## Tecnologias Utilizadas

* **Front-end:** 
    - **TypeScript:** linguagem de programação para criação tanto da aplicação mobile quanto da web;
    - **React Native:** biblioteca para desenvolvimento de sistemas Android e iOS de forma nativa;
    - **HTML:** linguagem de marcação para a criação do site;
    - **CSS:** linguagem para a estilização do site;
    - **React:** biblioteca para desenvolvimento de interfaces gráficas em páginas web.
* **Back-end:** 
    - **JavaScript:** linguagem de programação para contrução do Back-End;
    - **NodeJS:** para execução de JavaScript fora de um navegador web;
    - **MongoDB:** banco de dados NoSQL para pesistência de dados;
    - **Mongoose:** ORM em JavaScript para o MongoDB.
* **Outros:** 
    - **Figma:** ferramenta para criação do protótipo do projeto;

## Contribuições Pessoais

Fui desenvolvedor novamente no quinto semestre. Inicialmente, contribui com a minha equipe na criação dos modelos de entidade com Mongoose (ORM em JavaScript para MongoDB) e depois participei no desenvolvimento das funcionalidades de listagem, criação e edição de registro de ocorrência no Back-End. Após isso, fiz a parte da autenticação do usuário na aplicação mobile (com React Native) e seu Back-End (com NodeJS e a biblioteca jsonwebtoken). Depois, fiz a página de redefinição de senha tanto da versão mobile (com React Native) quanto da versão web (com React) e implementei também o Back-End (com NodeJS e a biblioteca bcrypt para a criptografia da senha). Além disso, auxiliei na criação do chat, no Back-End e no Front-End na versão web, e da implementação da página de relatório, utilizando a biblioteca victory no React e React Native para criação de gráficos. Por fim, trabalhei um pouco na parte de segurança da aplicação, criando a funcionalidade do termo de compromisso, na qual deve ser salvo no histórico a versão, por quem e quando ele foi aceito, além de mostrar um aviso ao usuário quando o termo for atualizado.

## Hard Skills

* **TypeScript** - sei fazer com auxílio de consultas;
* **React Native** - sei fazer com auxílio de consultas;
* **HTML5** - sei fazer com autonomia;
* **CSS3** - sei fazer com auxílio de consultas;
* **React** - sei fazer com auxílio de consultas;
* **JavaScript** - sei fazer com autonomia;
* **NodeJS** - sei fazer com autonomia;
* **Mongoose** - sei fazer com auxílio de consultas;
* **MongoDB:** - sei fazer com auxílio de consultas.

## Soft Skills

### Gestão de Tempo

Nesse semestre comecei a trabalhar, o que diminuiu meu tempo disponível para o projeto, fazendo ser essencial a gestão do meu tempo para que fosse possível eu realizar as atividades, buscando serem feitas durante o período de aula.

### Comunicação Efetiva

Com uma equipe com o máximo de integrantes (9), foi essencial termos uma comunicação efetiva dentro da equipe para que não nos perdessemos nas atividades restantes e para não fazermos a atividade duplicadamente.