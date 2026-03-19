# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Apresente os cenários de testes utilizados na realização dos testes da sua aplicação. Escolha cenários de testes que demonstrem os requisitos sendo satisfeitos.

Não deixe de enumerar os casos de teste de forma sequencial e de garantir que o(s) requisito(s) associado(s) a cada um deles está(ão) correto(s) - de acordo com o que foi definido na seção "2 - Especificação do Projeto". 

Por exemplo:
 
| **Caso de Teste** 	| **CT01 – Cadastrar perfil** 	|
|:---:	|:---:	|
|	Requisito Associado 	| RF-00X - A aplicação deve apresentar, na página principal, a funcionalidade de cadastro de usuários para que esses consigam criar e gerenciar seu perfil. |
| Objetivo do Teste 	| Verificar se o usuário consegue se cadastrar na aplicação. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://adota-pet.herokuapp.com/src/index.html<br> - Clicar em "Criar conta" <br> - Preencher os campos obrigatórios (e-mail, nome, sobrenome, celular, CPF, senha, confirmação de senha) <br> - Aceitar os termos de uso <br> - Clicar em "Registrar" |
|Critério de Êxito | - O cadastro foi realizado com sucesso. |
|  	|  	|
| Caso de Teste 	| CT02 – Efetuar login	|
|Requisito Associado | RF-00Y	- A aplicação deve possuir opção de fazer login, sendo o login o endereço de e-mail. |
| Objetivo do Teste 	| Verificar se o usuário consegue realizar login. |
| Passos 	| - Acessar o navegador <br> - Informar o endereço do site https://adota-pet.herokuapp.com/src/index.html<br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" |
|Critério de Êxito | - O login foi realizado com sucesso. |


**MODELO EM CONSTRUÇÃO**
| Caso de Teste | CT01 – Cadastrar perfil |
|:---:|:---:|
| Requisito Associado | RF-001 - Cadastro de usuários |
| Objetivo do Teste | Verificar se o usuário consegue se cadastrar na aplicação. |
| Passos | - Acessar o navegador <br> - Informar o endereço do site <br> - Clicar em "Criar conta" <br> - Preencher os campos obrigatórios (e-mail, nome, sobrenome, celular, CPF, senha, confirmação de senha) <br> - Aceitar os termos de uso <br> - Clicar em "Registrar" |
| Critério de Êxito | - O cadastro foi realizado com sucesso. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT02 – Efetuar login |
|:---:|:---:|
| Requisito Associado | RF-002 - Autenticação de usuários |
| Objetivo do Teste | Verificar se o usuário consegue realizar login. |
| Passos | - Acessar o navegador <br> - Informar o endereço do site <br> - Clicar no botão "Entrar" <br> - Preencher o campo de e-mail <br> - Preencher o campo da senha <br> - Clicar em "Login" |
| Critério de Êxito | - O login foi realizado com sucesso. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT03 – Cadastrar serviço |
|:---:|:---:|
| Requisito Associado | RF-003 - Gerenciamento de serviços |
| Objetivo do Teste | Verificar se o profissional consegue cadastrar um serviço. |
| Passos | - Acessar o sistema <br> - Realizar login como profissional <br> - Acessar a área de serviços <br> - Clicar em "Cadastrar serviço" <br> - Preencher nome, descrição, duração e valor <br> - Clicar em "Salvar" |
| Critério de Êxito | - O serviço foi cadastrado com sucesso. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT04 – Realizar agendamento |
|:---:|:---:|
| Requisito Associado | RF-005 - Realização de agendamentos |
| Objetivo do Teste | Verificar se o cliente consegue agendar um serviço. |
| Passos | - Acessar o sistema <br> - Realizar login como cliente <br> - Buscar um serviço <br> - Selecionar profissional <br> - Escolher data e horário <br> - Confirmar agendamento |
| Critério de Êxito | - O agendamento foi realizado com sucesso. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT05 – Cancelar agendamento |
|:---:|:---:|
| Requisito Associado | RF-006 - Cancelamento de agendamentos |
| Objetivo do Teste | Verificar se o usuário consegue cancelar um agendamento. |
| Passos | - Acessar o sistema <br> - Realizar login <br> - Acessar agenda <br> - Selecionar agendamento <br> - Clicar em "Cancelar" |
| Critério de Êxito | - O agendamento foi cancelado com sucesso. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT06 – Buscar profissionais |
|:---:|:---:|
| Requisito Associado | RF-007 - Busca de profissionais e serviços |
| Objetivo do Teste | Verificar se o cliente consegue buscar profissionais. |
| Passos | - Acessar o sistema <br> - Utilizar a barra de busca <br> - Inserir nome ou serviço <br> - Clicar em buscar |
| Critério de Êxito | - Os resultados da busca são exibidos corretamente. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT07 – Visualizar agenda |
|:---:|:---:|
| Requisito Associado | RF-008 - Visualização da agenda do cliente |
| Objetivo do Teste | Verificar se o cliente consegue visualizar seus agendamentos. |
| Passos | - Acessar o sistema <br> - Realizar login <br> - Acessar área de agenda |
| Critério de Êxito | - Os agendamentos são exibidos corretamente. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT08 – Avaliar profissional |
|:---:|:---:|
| Requisito Associado | RF-009 - Sistema de avaliações |
| Objetivo do Teste | Verificar se o cliente consegue avaliar um profissional. |
| Passos | - Acessar o sistema <br> - Realizar login <br> - Acessar serviço concluído <br> - Inserir nota e comentário <br> - Confirmar avaliação |
| Critério de Êxito | - A avaliação foi registrada com sucesso. |
 
|  |  |
|:---:|:---:|

| Caso de Teste | CT09 - Visualizar perfil do profissional |
|:---:|:---:|
| Requisito Associado | RF-010 - Perfil público de profissionais |
| Objetivo do Teste | Verificar se o perfil do profissional é exibido corretamente. |
| Passos | - Acessar o sistema <br> - Buscar um profissional <br> - Acessar o perfil |
| Critério de Êxito | - Informações, serviços e avaliações são exibidos corretamente. |

|  |  |
|:---:|:---:|

| Caso de Teste | CT10 – Receber notificação |
|:---:|:---:|
| Requisito Associado | RF-012 - Notificações automáticas |
| Objetivo do Teste | Verificar se o usuário recebe notificações do sistema. |
| Passos | - Realizar um agendamento <br> - Alterar ou cancelar o agendamento |
| Critério de Êxito | - O usuário recebe notificação da ação realizada. |
 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)
