# Plano de Testes de Software

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>

Alguns dos requisitos para realização dos testes de software são:
- Site publicado na Internet 
- Navegador da Internet - Chrome, Firefox, Edge, Opera GX e derivados
- Conectividade de Internet para acesso às plataformas (APIS)

 
## Ferramentas de Testes
Utilizamos como ferramenta o programa Visual Studio Code e o navegador EDGE.

Todos os membros tiveram participação ativa nos testes, tanto via encontro online, quanto por reunião por meio de chat online. Abaixo detalhamos com descrição todos os testes funcionais que foram realizados.

| Caso de Teste | CT-01-Visualizar página principal |
| ------------- | ------------- |
| Requisitos Associados  |  RF-01- O cabeçalho será fixo, acompanhando o usuário por toda home page ao usar a barra de rolagem. Nele irá conter aba de login, notificação e botão home, além do logo e as redes sociais do projeto. ; RF-02 - Deverá conter na página principal 3 cards que permita a inscrição de ONGs e voluntários para a realização e disponibilização de atividades;   RF-03 - O site deve apresentar uma imagem (thumbnail) e uma descrição correspondente ao assunto apresentado;  RF-04 - Ao ampliar ou reduzir os valores do zoom o site deverá manter sua responsividade;  RF-05 Espaço disponível para o usuário entrar em contato e/ou tirar dúvidas relacionadas ao projeto, os campos obrigatórios de preenchimento serão: nome, e-mail e mensagem; RF-06 - O rodapé fixo estará presente em todas as abas do site, contendo um campo de inscrição de e-mail para recebimento de newsletter e o logo daPuc Minas.|
| Objetivo do Teste  | Verificar se todas as abas e ícones estão direcionando para as páginas corretas.|
| Passos | 1) Acessar o Navegador; 2) Informar o endereço do Site; 3) Visualizar a página principal |
| Critérios de Êxito | ● O usuário, ao clicar no card que mais se identifica, será direcionado para a aba específica que quer se inscrever. ● Todos os ícones e abas devem estar direcionando para os locais corretos.   ● No espaço para contato e/ou dúvidas, caso o campo obrigatório não seja preenchido, aparecerá um tooltip com a notificação: Preencha este campo.      ● No campo de inscrição de e-mail para recebimento de newsletter, se não for preenchido, aparecerá um tooltip com a mensagem: Preencha este campo.   ● Ao clicar no logo da Puc Minas, o usuário será direcionado para um link externo. (https://icei.pucminas.br) |



| Caso de Teste | CT-02-Abrir a aba de login |
| --- | --- |
| Requisitos Associados | RF-07 - A aba de login deve permitir ao usuário a inserção dos dados (e-mail e senha) para acessar seu perfil no site. |
| Objetivo do Teste | Verificar se o login será realizado corretamente, obedecendo às regras pré-definidas. |
| Passos | 1) Acessar o Navegador; 2) Informar o endereço do Site; 3) Visualizar a página principal; 4) Clicar na aba de login |
| Critérios de Êxito | ● E-mail: conter um domínio após o uso do @; ● Senha: conter pelo menos 1 letra maiúscula,1 letra minúscula, 1 número, 1 caracter especial (@!#$%&) e mínimo de 8 dígitos; ● Ao não obedecer as regras de preenchimento de campo, será gerado um tooltip com a notificação: “Preencha este campo.". |



| Caso de Teste | CT-03-Notificações |
| --- | --- |
| Requisitos Associados | RF-08 - Esta aba deve apresentar ao usuário às notificações do site, como: vagas inscritas, novas vagas, novas atividades, novos voluntários etc. |
| Objetivo do Teste | Avaliar se as notificações estão chegando ao perfil de todos os usuários cadastrados. |
| Passos | 1) Acessar o Navegador; 2) Informar o endereço do Site; 3) Visualizar a página principal; 4) Clicar na aba de notificações. |
| Critérios de Êxito | Exibir todas as notificações do site. |



| Caso de Teste | CT-04-Aba Home |
| --- | --- |
| Requisitos Associados | RF-09 Esta aba deve direcionar o usuário para a página inicial, independente de qual parte do site ele está acessando. |
| Objetivo do Teste | Verificar se o usuário está sendo direcionado para a página inicial do site. |
| Passos | 1) Acessar o Navegador; 2) Informar o endereço do Site; 3) Navegar pelo site; 4) Clicar na aba ”home”. |
| Critérios de Êxito | Estar navegando em qualquer aba do site. |


| Caso de Teste | CT-05-ONG Voluntariada |
| --- | --- |
| Requisitos Associados | RF-10 - Permitir que as ONGs cadastrem suas atividades, a fim de receber as inscrições de novos usuários.|
| Objetivo do Teste | ● Verificar se a aba está disponível para que as ONGs possam se cadastrar. ● Verificar se a seção está gerando o anúncio das ONGs. |
| Passos | 1) Acessar o Navegador 2) Informar o endereço do Site 3) Acessar a página principal 4) Clicar na aba de ONGs voluntariadas |
| Critérios de Êxito | A página deve apresentar nome, descrição e requisitos da vaga disponível, além de um mapa de localização para facilitar o acesso do voluntário até o local da atividade, e também uma imagem de destaque da vaga em questão. |


| Caso de Teste | CT-06- Seja voluntário |
| --- | --- |
| Requisitos Associados | ●RF-11 - Permitir que os usuários inscrevam-se e tornem-se voluntários. ●RF-12 - Será apresentada uma imagem correspondente à vaga em questão
(thumbnail).|
| Objetivo do Teste |● Verificar se a aba está disponível para que os futuros voluntários possam cadastrar-se. ● Verificar se a barra de busca por localização está disponibilizando corretamente as regiões, assim o usuário poderá escolher a de sua preferência. |
| Passos | 1) Acessar o Navegador 2) Informar o endereço do Site 3) Acessar a página principal 4) Clicar na aba “Seja Voluntário” |
| Critérios de Êxito | ● A barra de busca apresentada poderá ser utilizada para filtrar a localização desejada. ● Ao clicar nas setas direcionadas para esquerda e para direita, o site deve alterar as vagas que serão apresentadas. ● Deverá conter imagens visíveis associadas às vagas destacadas. ● Ao ser direcionado para a vaga em questão, será apresentado nome, descrição e requisitos da vaga disponível, um mapa de localização para facilitar o acesso do voluntário até o local da atividade, e a imagem de destaque desta vaga. |






| Caso de Teste | CT-06-Atividades |
| --- | --- |
| Requisitos Associados | RF-13 - Permitir que os usuários inscrevam-se nas atividades disponíveis; RF-14 - Será apresentada uma imagem (thumbnail) e, logo abaixo, uma pequena descrição correspondente à atividade em questão. |
| Objetivos do Teste | 1) Verificar se a aba está disponível para que os voluntários possam cadastrar-se nas atividades; 2) Verificar se a barra de filtro está apresentando as classes de atividades disponíveis; 3) Verificar se as atividades estão sendo exibidas para o usuário. |
| Passos | 1) Acessar o Navegador; 2) Informar o endereço do Site; 3) Acessar a página principal; 4) Clicar na aba “Atividades”. |
| Critérios de Êxito | 1) A barra de busca por filtro deverá apresentar as atividades separadas por classes, como: esporte, saúde, limpeza etc; 2) Deverá conter imagens visíveis e um pequeno texto associados às atividades disponíveis; 3) Ao escolher a atividade de interesse, o usuário será direcionado para o site externo daquela atividade, onde será apresentada mais informações sobre a vaga em questão. |
