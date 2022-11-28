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
  
  ![imagem_2022-11-27_220955395](https://user-images.githubusercontent.com/114962362/204171414-0e0751da-01ae-4ff6-8a17-76fc1cf7868a.png)
> *- Redirecionamento de páginas*

* CONSIDERAÇÕES: Foi constatado êxito no teste de redirecionamento.
  


>> ![TESTE  - PAG INICIAL - VISUALIZAÇÃO - OBRIGATORIO 3](https://user-images.githubusercontent.com/114964435/204155452-650e9362-9467-411b-afb7-07ef87ea804c.png)
>> |RF-06 |
>> - O rodapé fixo estará presente em todas as abas do site, contendo umcampo de inscrição de e-mail para recebimento de newsletter e o logo da
Puc Minas.

* CONSIDERAÇÕES: Muitissímos sites acompanham um rodapé fixo com informações que o usuário pode necessitar a qualquer momento durante a navegação. Por conta disso, este rodapé está presente no site VOLUNTAR, para que de forma otimizada o usuário tenha a posibilidade de entrelaçar contatos com a aplicação. Recebendo newsletter via e-mail por exemplo. Além disso, a logo da PUC minas é um "atalho" clicável que irá lhe redirecionar para o seu site oficial e institucional. 



**CT-02-Login**
> ![image](https://user-images.githubusercontent.com/114962362/204172577-88066c19-2ff5-4df5-8148-233e82d6ed86.png)
>> | RF-07 |
>> - A aba de login deve permitir ao usuário a inserção dos dados 
(e-mail e senha) para acessar seu perfil no site.

Após o teste, foi constatado êxito.

![image](https://user-images.githubusercontent.com/114962362/204172961-e5f12ec5-f24b-4034-8497-79346c0429db.png)
> *- Domínio @ - OK*

![image](https://user-images.githubusercontent.com/114962362/204173479-011d46ce-204a-4248-b696-b2de3187379e.png)
> *- Preencher o campo - OK*



**CT-03-Notificações**
> ![imagem_2022-11-27_163827488](https://user-images.githubusercontent.com/114962362/204156048-b0205c0e-f983-4da8-b21e-20a8a5546cdd.png)
>> | RF-08 |
>> - Esta aba deve apresentar ao usuário às notificações do site, como: vagas inscritas, novas vagas, novas atividades, novos voluntários etc.
Após a realização do teste, foi constatado êxito.

* CONSIDERAÇÕES: Este teste foi realizado com o objetivo de constatar que todos os usuários cadastrados estejam recebendo as notificações do site, tais como: Novidades, vagas cadastradas, voluntários cadastrados, entre outros. Após realização do teste, foi obtido êxito.



**CT-04-Aba Home**
> ![imagem_2022-11-27_164119755](https://user-images.githubusercontent.com/114962362/204156153-81dc8399-9e46-4ae4-a3d4-aa68ad88ba6d.png)
>> | RF-09 |
>> - Esta aba deve direcionar o usuário para a página inicial, independente de qual parte do site ele está acessando.
Após a realização dos testes de navegação na página de notificação, o redirecionamento  ocorreu com sucesso para a página inicial através do botão de homepage.

* CONSIDERAÇÕES: Teste realizado com a intenção de testar a aba “home” que ficará disponível em todas as páginas do site, inclusive na própria página inicial. Uma vez que acionada na página inicial, não mudará de aba, havendo êxito no teste realizado.



**CT-05-ONG Voluntariada**
>![Untitled design (33)](https://user-images.githubusercontent.com/114962362/204166534-e1d35096-f921-47b9-abc6-10aab404f3c9.png)
>> | RF-10 |
>> - Permitir que as ONGs cadastrem suas atividades, a fim de receber as inscrições de novos usuários. Após a realização dos teste, constatamos que a área para cadastro de atividades de ONGs está funcionando de acordo com os critérios estabelecidos. Apresentando nome, imagem, descrição e requisitos. Presente nesta página também um mapa de localização via Google Maps.

* CONSIDERAÇÕES: Nesta aba, os testes tinham o propósito de testar a funcionalidade de cadastro das ONGs, além de verificar se estava disponibilizando os anúncios feitos pelas instituições, após testes, foi constatado êxito.



**CT-06-Seja Voluntário**
> ![imagem_2022-11-27_210023514](https://user-images.githubusercontent.com/114962362/204166898-0baf8fb2-b7c3-475c-80d0-c5f1c418e4d6.png)
> ![imagem_2022-11-27_210204989](https://user-images.githubusercontent.com/114962362/204167021-91c0632b-4ccc-47f3-9f2f-e2a6df4b4480.png)
>> | RF-11 |
>> | RF-12 |

* CONSIDERAÇÕES: Nesta página do site, a finalidade dos testes foi de garantir que, todos os voluntários interessados em participar de algum projeto consigam se cadastrar sem nenhum impedimento, além de testar a opção de pesquisar por localização, considerando a utilização de API “Google maps”.



**CT-07-Atividades**
> ![image](https://user-images.githubusercontent.com/114962362/204156252-3ea17d9d-af8a-42ec-8a74-4019f86c36ec.png)
>> | RF-13 |
>> -  Permitir que os usuários inscrevam-se nas atividades disponíveis.

>> ![image](https://user-images.githubusercontent.com/114962362/204156388-b7d48c1c-cccf-423a-8ed8-c8dd17f5a8c5.png)
>> | RF-14 |
>> - Será apresentada uma imagem (thumbnail) e, logo abaixo, uma pequena descrição correspondente à atividade em questão.

* CONSIDERAÇÕES: Nesta página do site, a intenção dos testes foi de garantir que, todas as atividades estejam visíveis, que os voluntários conseguem se cadastrar nas atividades e a funcionalidade da barra de filtros, havendo êxito nos testes realizados.



**CT-08-Contato**
![imagem_2022-11-27_212809111](https://user-images.githubusercontent.com/114962362/204168390-4b371a16-84a5-400d-a5d7-ac10b0e266a6.png)
![imagem_2022-11-27_212731294](https://user-images.githubusercontent.com/114962362/204168352-2320a62e-ef1e-4b96-9bfd-52c5a251988a.png)
![imagem_2022-11-27_212531807](https://user-images.githubusercontent.com/114962362/204168229-05c0bf05-f142-4f6e-99b5-a10b3556f39b.png)
![image](https://user-images.githubusercontent.com/114962362/204170441-12ecad8e-49fc-403d-a403-1b6c1c1f64eb.png)
>> | RF-15 |
>> - Permitir que os usuários possam entrar em contato em caso de dúvidas ou informações.

* CONSIDERAÇÕES: Houve a realização dos testes com o preenchimento dos campos obrigatórios e testes caso o usuário não preencha todos de forma correta. Após isso, foi constatado êxito.



**CT-09-Newsletter**
![image](https://user-images.githubusercontent.com/114962362/204168817-2590ad4d-f023-4867-8936-41835531db37.png)
![image](https://user-images.githubusercontent.com/114962362/204168870-2d8ede79-f7cd-4a6b-a347-d0e8ada52290.png)
>> | RF-16 | 
>> - Permitir que os usuários se inscreva para receber as campanhas de newsletter do Projeto Voluntar.

* CONSIDERAÇÕES: Após a realização dos testes, finalizado com êxito. Caso não obedeça a regra pré-definida, será gerado um tooltip com a notificação: “Preencha este campo.".
Está correto. Teste realizado com sucesso.


