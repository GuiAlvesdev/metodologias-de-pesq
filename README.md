<div align="center">

<h1> Portfólio das APIs - Guilherme Alves</h1>

<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/images/linux.png" alt="pingu" style="width:200px;height:200px;">


<h2  align="center">Sobre</h2>
Portfolio utilizado para apresentacao do projeto API na disciplina de Metodologia de Pesquisa Prof° Giuliano Araujo Bertoti






<h2  align="center"> Quem eu Sou</h2>

Comecei minha jornada na area de TI em 2015 atraves do meu primeiro tecnico em informatica atraves de uma iniciativa do governo de SP oferecendo cursos em diversos colegios, apos isso atuei como tecnico de TI, Analista de TI Jr e tambem desenvolvedor com enfase em Java a qual dedico maior parte dos estudos. atualmente atuo com a area de sustentacao
de ti, formado pela faculdade paulista em Analise e Desenvolvimento de Sistemas,cursando banco de dados pela FATEC de São josé dos Campos
o qual iniciei em 2022, nas horas vagas gosto de apreciar a natureza enquanto arrumo meu carro veio.


<h2  align="center"> Meus Projetos</h2>


<h2  align="center"> 3° Semestre</h2>


<p align="center">Empresa Parceira</p>

<a href="https://www.domrock.net/">
<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/domrock.jpg" alt="domrock" style="width:300px;height:300px;"></a>

<p>A DomRock foi a parceira do projeto do 3 semestre, a qual e uma software house com sede em sao jose dos campos-sp, destaque na cidade  e reconhecida no ranking de empresas BigData, a mesma propos um software web que fosse possivel fazer a manipulacao dos dados extraidos por uma IA e repassado a aplicacao para que seja gerenciada vendas</p>
<h3>Objetivo</h3>

O RockPlanning consiste em aplicação web que visando o gerenciamento das vendas de uma empresa, considerando o histórico do vendedor, o planejamento e as vendas realizadas. Deverá apresentar um comparativo dos dados mencionados anteriormente para que possam ser analisados de forma precisa e detalhada. Além disso, a aplicação será aprimorada com a adição de uma predição gerada por um algoritmo de Inteligência Artificial pré-existente, a fim de proporcionar maior precisão e confiabilidade, o vendedor tem acesso a plataforma atraves de login e senha anteriormente criados e disponibiliazados ao mesmo.




</div>

<h2  align="center" >Tecnologias Utilizadas</h2> 

<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/images/java.png" alt="java" height="64" width="64"><br> Java 17: Linguagem Principal do Back-end

<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/images/spring-boot.png" alt="java" height="64" width="64"><br> Spring Boot 2.4 :  Spring Boot é um framework que torna fácil a criação de aplicações Spring autossuficientes e robustas, possibilitando a execução imediata.

<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/images/js.png" alt="javascript" height="64" width="64"><br> JavaScript: linguagem para desenvolvimento da aplicação para front-end.

<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/images/mysql.png" alt="java" height="64" width="64" ><br> MySQL: SGBD para desenvolvimento do Banco de Dados.

<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/images/trello.png" alt="java" height="64" width="64" ><br> Trello: ferramenta utilizada para a Gestão de Projetos utilizando a metodologia Scrum.

<img src="https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/blob/main/images/slack.png" alt="java" height="64" width="64"><br> slack:  um serviço de mensagens instantâneas multiplataforma.


<div align="center">

</div>

<h2  align="center">Contribuições Pessoais</h2>

Desempenhei junto a equipe do back-end focado na construcao de uma aplicacao Rest utilizando a linguagem java e seu framework Spring-Boot, desenvolvendo os end-points da aplicacao, utilizando os padroes de projeto como MVC, REST, seguranca da aplicacao, autenticacao de um usuario, gerenciar de forma efetiva excessoes disparadas pela mesma, testes manuais, como ja tinha experiencia utilizando o principal framework que seria utilizado no projeto e linguagem, tive um papel chave para trablhar junto aos demais como seria a melhor abordagem com problemas que foram aparecendo conforme o projeto foi se destrinchando, abaixo algumas principais partes que ajudei a implementar e uma breve descricao.



* Arquitetura Rest


![image](https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/assets/72584502/18751f2a-cd43-4efd-8405-319c00e49f5d)




 *  No exemplo acima temos um endpoint controller um exemplo de como o framework do spring simplifica a construcao de uma aplicacao Rest, tornando o desenvolvimento de uma API muito mais rapida, o que e o REST? REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas conforme o projeto. No exemplo acima quando um vendedor faz  um cadastro de uma nova venda usando o endpoint, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint no caso por esse endpoint para criar um novo planejamento de venda. Essa informação (ou representação) é entregue via HTTP utilizando um dos vários formatos possíveis neste caso utilizando o padrao Json um dos mais utilizados atualmente, se o mesmo for criado a solicitacao retorna uma resposta HTTP Ok com a numeracao 201, o que nos padrao de solicitacao significa que obtve sucesso na sua criacao.


* Padrao DTO

![builder](https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/assets/72584502/557e4635-6f33-4655-950a-16d9282ce146)







* Um outro exemplo do codigo que ajudei a implementar se refere ao padrao DTO, mas o que seria o padrao DTO? DTO (Data Transfer Object) é um padrão de software voltado para a transferência de dados entre as camadas de uma aplicação. Ele consiste basicamente no entendimento de como as informações trafegam dentro de um sistema, o padrao e como se fosse uma camada a mais de protecao, o que impede a manipulacao direta da classe modelo da aplicacao, consequente impede que a camada modelo seja manipulada diretamente pela de servico e nos permite poder manipular os dados que desejamos obter ao manipular a classe, um exemplo imagine que voce precisa retorno de uma venda por exemplo, mas so precisa de apenas de datas e vendas, e nao todos os dados diretamente da classe, utilizar o padrao DTO deixa este trabalho mais flexivel, no caso acima pegamos apenas os dados que eram necessarios da camada modelo, para a criacao de uma nova venda de planejamento, utilizando o DTO.



* Camada Service


![camadaservice](https://github.com/GuiAlvesdev/portfoliobancodedadosfatec/assets/72584502/63bf1f18-ab10-46da-9a93-8b7648a251e2)





* quando construimos uma aplicacao e essencial separar as camadas seja o model, reepository, service, a camada de servico ou service, O termo “service” normalmente é associado a diversas coisas: sejam web services, SOAP, REST ou gRPC. Até mesmo o DDD trabalha com domain e application services. Ela e onde normalmente fica toda as regras de negocio da aplicacao e manipulacao de acesso ao banco, acima um bom exemplo de como foi utilizado a camada service onde fazemos a criacao de um novo planejamento e chamamos a camada que persiste no banco de dados.







<h2 align="center">Lições Aprendidas</h2> 
Tive o meu primeiro contato de forma pratica em um projeto utilizando  JAVA 17 e seu framework spring-boot junto com todo seu ecossistema, algo que eu havia ja estudado por um tempo e feito apenas projetos menores e de autoria propria, sendo assim foi de grande importancia, os erros me mostraram a importancia de buscar melhor a documentacao das versoes para adaptar o projeto sem erros, visto que a propria documentacao do spring o qual foi utilizado na maioria das vezes nao se aprofunda em explicar o que foi depreciado e qual o correto caminho para atualizar os projetos com versoes antigas, sendo assim a importancia de se manter atualizado na area de TI se torna o papel chave, uma rotina de estudos constantes e ter a humildade de tirar duvida com outras pessoas, mudando toda minha pespectiva de que nem sempre devemos seguir apenas um caminho, mas poder ir a fundo e contornar e pensar em maneiras de se solucionar um problema.






