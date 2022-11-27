# Registro de Testes de Software

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>, <a href="8-Plano de Testes de Software.md"> Plano de Testes de Software</a>

Os relatórios obtidos nos testes de software realizados são descritos abaixo.

## Avaliação

Discorra sobre os resultados do teste. Ressaltando pontos fortes e fracos identificados na solução. Comente como o grupo pretende atacar esses pontos nas próximas iterações. Apresente as falhas detectadas e as melhorias geradas a partir dos resultados obtidos nos testes.

> **CT-01-Visualizar página principal**
> ![TESTE  - RESPONSIVIDADE](https://user-images.githubusercontent.com/114964435/204152093-ac5a07e1-7dc6-4c79-87b0-2b206870d0b2.png)
>> |RF-01 |
>> - O cabeçalho será fixo, acompanhando o usuário por toda home page ao usar a barra de rolagem. Nele irá conter aba de login, notificação e 
botão home, além do logo e as redes sociais do projeto. 

* CONSIDERAÇÕES:  Após a realização dos testes, percebe-se que os critérios são respeitados e estão todos funcionais. O cabeçalho sem mantém fixo sem alterar ou prejudicar a estrutura da aplicação durante todo o scroll de tela. Os ícones mencionados acima acompanham o cabeçalho. O aprimoramento que poderá ocorrer tem relação com a fonte aplicada e organização espacial dos ícones.


>> ![TESTE  - 3 CARDS](https://user-images.githubusercontent.com/114964435/204152525-1ab05862-6392-493a-a66e-d9c71122a638.png)
>> | RF-02 |
>> - Deverá conter na página principal 3 cards que permita a inscrição de ONGs e voluntários para a realização e disponibilização de atividades.
>> 
>> | RF-03 | 
>> - O site deve apresentar uma imagem (thumbnail) e uma descrição correspondente ao assunto apresentado.

* CONSIDERAÇÕES: Os três cards são dispostos na página principal sem nenhuma má formatação. Com possibilidade de clicar e ser redirecionado para três campos do site.
      Toda a formatação, isso inclui thumbnail e descrição, estão bem relacionadas com o seu respectivo CARD. 

>> 25% de zoom
>> ![TESTE  - 3 CARDS](https://user-images.githubusercontent.com/114964435/204154993-662e600d-b21b-4989-949d-402d702ef918.png)
>> 100% de zoom
>> ![TESTE  - 3 s](https://user-images.githubusercontent.com/114964435/204155072-ca0340f2-9033-48a8-a39a-978fbef23a2b.png)
>> | RF-04 |
>> - Ao ampliar ou reduzir os valores do zoom o site deverá manter sua responsividade.

* CONSIDERAÇÕES: O zoom em uma aplicação pode ser um dos fatores da má formação ou má visualização do conteúdo. Portanto, um dos pontos principais do site é manter a sua responsividade. Independentemente se o usuário está utilizando via dispositivo móvel, computador, tablet etc. Todo o conteúdo irá se adaptar sem comprometer a formatação do site. Neste caso o nosso teste obteve êxito. 



>> ![TESTE  - PAG INICIAL - VISUALIZAÇÃO - OBRIGATORIO 2](https://user-images.githubusercontent.com/114964435/204155299-7546e014-5f19-4d52-b037-5b5ad5966a40.png)
>> |RF-05 |
>> - Espaço disponível para o usuário entrar em contato e/ou tirar dúvidas relacionadas ao projeto, os campos obrigatórios de preenchimento serão:
nome, e-mail e mensagem. 

* CONSIDERAÇÕES: Um dos testes necessários era com relação ao preenchimento dos campos na área para contato. Existem diversos cenários que podem ocorrer.
  Primeiro, o usuário pode escrever seu e-mail incorretamente, faltando elementos como o @; Pode acabar esquecendo de preencher um dos campos e nesse caso isso compromete o envio de uma dúvida, contato etc. A comunicação é afetada.
  Por conta disso um dos nossos testes está envolto na obrigatoriedade de preenchimento dos campos principais. O teste obteve êxito.
  

>> ![TESTE  - PAG INICIAL - VISUALIZAÇÃO - OBRIGATORIO 3](https://user-images.githubusercontent.com/114964435/204155452-650e9362-9467-411b-afb7-07ef87ea804c.png)
>> |RF-06 |
>> - O rodapé fixo estará presente em todas as abas do site, contendo umcampo de inscrição de e-mail para recebimento de newsletter e o logo da
Puc Minas.

* CONSIDERAÇÕES: Muitissímos sites acompanham um rodapé fixo com informações que o usuário pode necessitar a qualquer momento durante a navegação. Por conta disso, este rodapé está presente no site VOLUNTAR, para que de forma otimizada o usuário tenha a posibilidade de entrelaçar contatos com a aplicação. Recebendo newsletter via e-mail por exemplo. Além disso, a logo da PUC minas é um "atalho" clicável que irá lhe redirecionar para o seu site oficial e institucional. 




**CT-03-Notificações**
> ![imagem_2022-11-27_163827488](https://user-images.githubusercontent.com/114962362/204156048-b0205c0e-f983-4da8-b21e-20a8a5546cdd.png)
>> | RF-08 |
>> - Esta aba deve apresentar ao usuário às notificações do site, como: vagas inscritas, novas vagas, novas atividades, novos voluntários etc.
Após a realização do teste, foi constatado êxito.

**CT-04-Aba Home**
> ![imagem_2022-11-27_164119755](https://user-images.githubusercontent.com/114962362/204156153-81dc8399-9e46-4ae4-a3d4-aa68ad88ba6d.png)
>> | RF-09 |
>> - Esta aba deve direcionar o usuário para a página inicial, independente de qual parte do site ele está acessando.
Após a realização dos testes de navegação na página de notificação, o redirecionamento  ocorreu com sucesso para a página inicial através do botão de homepage.





**CT-06-Atividades**
> ![image](https://user-images.githubusercontent.com/114962362/204156252-3ea17d9d-af8a-42ec-8a74-4019f86c36ec.png)
>> | RF-13 |
>> -  Permitir que os usuários inscrevam-se nas atividades disponíveis.

* CONSIDERAÇÕES
>> ![image](https://user-images.githubusercontent.com/114962362/204156388-b7d48c1c-cccf-423a-8ed8-c8dd17f5a8c5.png)
>> | RF-14 |
>> - Será apresentada uma imagem (thumbnail) e, logo abaixo, uma pequena descrição correspondente à atividade em questão.





