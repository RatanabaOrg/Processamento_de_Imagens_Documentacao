<div align="center" id="menu">

![logo](https://github.com/RatanabaOrg/documentacao/assets/100284976/3b3af8d0-a426-4abc-a3a4-d9f7981e3a5a)

<h3> Aplicação mobile para registro e quantificação de pragas em campos agrícolas </h3>

<p>
    <a href="#sobre">Sobre</a> | <a href="#backlog">Backlogs</a> | <a href="#manuais">Manuais</a> | <a href="#modelo">Diagrama</a> | <a href="#equipe">Equipe</a>
</p>

<br>

 <a href="https://pt-br.reactjs.org/" target="blank"><img align="center" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="react native"/></a> 
 <a href="https://nodejs.org/en/about/" target="blank"><img align="center" src="https://img.shields.io/badge/Node.js-20232A?style=for-the-badge&logo=node.js&logoColor=43853D" alt="nodejs"/></a>
 <a href="https://www.python.org/" target="blank"><img align="center" src="https://img.shields.io/badge/Python-20232A?style=for-the-badge&logo=python&logoColor=blue" alt="Python"/></a>
 <a href="https://firebase.google.com/?hl=pt" target="blank"><img align="center" src="https://img.shields.io/badge/Firebase-20232A?style=for-the-badge&logo=firebase&logoColor=F7DF1E" alt="Firebase"/></a>
 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML" target="blank"><img align="center" src="https://img.shields.io/badge/HTML5-20232A?style=for-the-badge&logo=html5&logoColor=orange" alt="html"/></a>
 <a href="https://developer.mozilla.org/pt-BR/docs/Web/CSS" target="blank"><img align="center" src="https://img.shields.io/badge/CSS3-20232A?style=for-the-badge&logo=css3&logoColor=blue" alt="css"/></a> <br><br>
 <a href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript" target="blank"><img align="center" src="https://img.shields.io/badge/JavaScript-20232A?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javascript"/></a> 
 <a href="http://www.figma.com" target="blank"><img align="center" src="https://img.shields.io/badge/Figma-20232A?style=for-the-badge&logo=figma&logoColor=white" alt="figma"/></a> 
 <a href="https://code.visualstudio.com/" target="blank"><img align="center" src="https://img.shields.io/badge/Visual_Studio_Code-20232A?style=for-the-badge&logo=visual%20studio%20code&logoColor=blue" alt="vsc"/></a> 
 <a href="https://github.com/" target="blank"><img align="center" src="https://img.shields.io/badge/GitHub-20232A?style=for-the-badge&logo=github&logoColor=white" alt="github"/></a> 
 <a href="https://www.atlassian.com/br/software/jira/guides/getting-started/introduction" target="blank"><img align="center" src="https://img.shields.io/badge/Jira-20232A?style=for-the-badge&logo=Jira&logoColor=blue" alt="jira"/></a>

</div> 

<br>

<span id="sobre">

## :pencil: Sobre o projeto

 O projeto propõe uma solução para um dos desafios fundamentais na agricultura brasileira: a contagem precisa de pragas nos campos. Atualmente, esse processo é feito manualmente, o que consome tempo e recursos. Com o intuito de simplificar essa tarefa, planejamos desenvolver um aplicativo que permitirá localizar armadilhas, capturar fotos e em seguida, processá-las para determinar a quantidade de pragas presentes. Essa iniciativa proporcionará aos agricultores informações mais rápidas e precisas sobre a aplicação de defensivos agrícolas, além de possibilitar um monitoramento mais eficiente das armadilhas utilizadas.

Confira a idealização inicial do projeto:

 - Mockup: clique em [link]([https://www.figma.com/file/Z8cq5p8fAsvwqpAnGYiIhp/%F0%9F%90%B6-Ratanaba-%F0%9F%A6%B4?type=design&node-id=0%3A1&mode=design&t=abjt9pcSr3BCzQ38-1](https://www.figma.com/file/3lNlsnaBP7DkxzIIA7MGMz/api-5-Visiona?type=design&node-id=101-2&mode=design&t=6Q8tlAtnp1GMS03l-0)) e veja através do Figma
 - Protótipo navegável das telas do administrador: [navegue]([https://www.figma.com/proto/Z8cq5p8fAsvwqpAnGYiIhp/%F0%9F%90%B6-Ratanaba-%F0%9F%A6%B4?type=design&node-id=1-138&t=abjt9pcSr3BCzQ38-0&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=1%3A138](https://www.figma.com/proto/3lNlsnaBP7DkxzIIA7MGMz/api-5-Visiona?type=design&node-id=152-4847&t=dK9D6RtiEPNcLqvm-0&scaling=scale-down&page-id=152%3A2818&starting-point-node-id=152%3A4847&show-proto-sidebar=1)) entre as páginas

<br>

<span id="backlog">  

## :pushpin: Backlog do Produto  

 #### Épicos (Requisitos Funcionais) 

| SPRINT | CÓDIGO | DESCRIÇÃO                                                                     |
| :----: | :----: | :---------------------------------------------------------------------------- |
|   1    |  RF1   | Interface de cadastro cliente                                                 |
|   1    |  RF2   | Interface para cadastro de informações espaciais e alfanuméricas de campo     |
|   2    |  RF3   | Aplicação para localização de informações espaciais, em campo                 |
|   2    |  RF4   | Aplicação para obtenção de fotos pela câmera                                  |
|   2    |  RF5   | Sincronização dos dados do app com banco de dados                             |
|   3    |  RF6   | Detecção se há pragas nas imagens                                             |
|   3    |  RF7   | Contagem de pragas em nas imagens                                             |
|   3    |  RF8   | Mapeamento da ocorrência pragas                                               |
|   4    |  RF9   | Dashboard de indicadores de registro de pragas em armadilhas de campo         |
|   4    |  RF6   | Rotina para envio de alertas ao WhatsApp do agricultor                        |

#### Requisitos Não Funcionais  

| CÓDIGO | DESCRIÇÃO                                                                 |
| :----: | :------------------------------------------------------------------------ |
|  RNF1  | Modelo treinado e desenvolvido para o mapeamento das pragas em armadilhas |

#### Tecnologias Desejáveis  

| CÓDIGO | DESCRIÇÃO             |
| :----: | :-------------------- |
|  TD1   | Hospedagem em nuvem   |
|  TD2   | Android SKD           |

<br>

<span id="modelo">

 ## :cloud: Modelo do banco de bados

![diagrama](https://github.com/RatanabaOrg/documentacao/assets/100284976/00fa0657-2b86-406e-877b-2205e782db78)

 <br>

 <span id="manuais">

 ## :scroll: Manual de instalação e do usuário

* Depois de instalar as tecnologias necessárias para o projeto (NodeJS e Android Studio) digite no cmd:

  ```
  git clone https://github.com/RatanabaOrg/front_end.git
  npm install
  npx react-native run-android
  ```
  
* Ou baixe o executável em seu celular.

* PFD ou Word aqui explicando como usar o app.

 <br>

<span id="equipe"> 

## :busts_in_silhouette: Equipe

|           Nome            |                      LinkedIn & GitHub                       |
| :-----------------------: | :----------------------------------------------------------: |
| Amanda Vieira de Oliveira | Product Owner |  [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/amanda-vo/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/amandavo) |
| Lucas França Registro | Scrum Master | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/LucasFrancaRegistro) |
| Carlos Eduardo Falandes | Dev Team | [![Lattes Badge](https://img.shields.io/badge/-Lattes-orange?style=flat-square&logo=GitBook&logoColor=white&link=http://lattes.cnpq.br/2433599000300626)](http://lattes.cnpq.br/3579183651868833) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Desduh) |
| Júlia Sousa Gayotto | Dev Team | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/júlia-gayotto/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JuliaGayotto) |

<a href="#menu">Voltar ao topo</a>
