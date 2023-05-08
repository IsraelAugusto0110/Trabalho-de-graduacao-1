# Trabalho-de-graduacao-1

# Israel Augusto

## Introdução

Olá, me chamo Israel Augusto, estou cursando o Análise e Desenvolvimento de Sistemas na Fatec - Profº Jessen Vidal. estes são alguns dos projetos que meus colegas e eu desenvolvemos durante os 5 primeiros semestres de nossa graduação.

## Meus Projetos

### Em 2019-2
#### Nome do projeto: Lumém
#### Empresa parceira: Fatec

O projeto desenvolvido neste semestre teve como temática ‘Sistemas Automatizados 4.0”, ou seja, criar uma solução de Iot(Internet of Things) que integrasse componentes de hardware e software para automação residencial, como por exemplo ligar e desligar lâmpada, controle de temperatura ambiente, etc. Por ser nosso primeiro semestre e por que a metodologia de aprendizado por API estava no início, nossa empresa parceira foi a própria Fatec. Tivemos a orientação do professor Jean Carlos que nos indicou as melhores tecnologias, de acordo com o nível de nossos conhecimentos. Utilizamos para o frontend a ferramenta App Inventor para criar uma interface de usuário simples, e para o backend, além do Firebase para o banco de dados e a IDE do Arduino para o código que controla os componentes de hardware. Na aplicação final, o usuário utiliza o app para dispositivos moveis que envia os comandos para a placa de Arduino, através de sinal bluetooth.

- [GIT](https://github.com/IsraelAugusto0110/Lumem)

- A seguir é apresentada a tela do aplicativo.

<img src="https://github.com/IsraelAugusto0110/Trabalho-de-graduacao-1/blob/main/Images/TelaLumem.png" width="200" />

#### A equipe era formada por:

- Wesley Dias(Scrum Master)
- Denis Lima(PO)
- Israel Augusto(Developer)
- Leonardo Andrade(Developer)


#### Tecnologias Utilizadas

Backend:
- [Arduino IDE](https://www.arduino.cc/en/software) : Editor de codigo em C++ que facilita a codificação e permite fazer o upload para a placa de arduino. Compativel com todos os modelos de placas arduino, escreve-se o codigo apenas uma vez;
- [Firebase](https://console.firebase.google.com/) : Oferece um banco de dados em nuvem, de facil utilização, ideal para um projeto pequeno como este, pois precisavamos apenas armazenar as avaliações do usuarios;
- C++: Linguagem de programação padrão das placas arduino;
Frontend:
- [App Inventor](https://appinventor.mit.edu/) : Ferramenta desenvovida pela Google para criação de aplicações mobile basicas, com foco em aprendizado, permite arrastar os componentes para gerar estruturas de codigo simples. Ideal para criação de prototipos;
- Hardwware
- - Arduino Uno : placa microcontroladora de facil utilização;
- - Modulo Bluetooth: permite comunicação sem fio entre o app e a placa de arduino.

#### Contribuições Pessoais

Contribui tanto no backend, quanto no frontend da aplicação. No backend, escrevi parte do codigo em C++.

#### Hard Skills
- C++ - Sei fazer com autonomia
- Tecnologias mobile - Sei fazer com autonomia
- Conceitos de Hardware - Sei fazer com autonomia

#### Soft Skills

- Trabalho em equipe - Colaboração e troca de informações foram essenciais em todas as fases do projeto.
- Aprendizado continuo - Foi necessario aprender varias tecnologias que até então tinha apenas ouvido falar, é essencial manter a mente aberta.

### Em 2020-1
#### Nome do projeto: Algo Positivo
#### Empresa parceira: Spc serasa

Foi criado um programa que analisa os pagamentos dos clientes e envia por e-mail um arquivo em formato CSV contendo as informações dos clientes da empresa. O e-mail é enviado para os colaboradores da empresa SPC Brasil da área de marketing. A área de marketing da empresa com essas informações em mãos, terá um auxílio nas decisões a respeito de oferecer ou não novos produtos e serviços para determinados clientes, de acordo com as informações dos clientes, se são bons ou maus pagadores.

- [GIT](https://github.com/IsraelAugusto0110/Algo-Positivo.git)

- A seguir é apresentada um gif do aplicativo em funcionamento.

<img src="https://github.com/IsraelAugusto0110/Trabalho-de-graduacao-1/blob/main/Images/Previa0.gif" width="1000" />

#### A equipe era formada por:

- Wesley Dias(Scrum Master)
- Denis Lima(Developer)
- Israel Augusto(Scrum Master)
- Natalia Biscaro(Developer)
- Euclides Resende(Developer)

#### Tecnologias Utilizadas
Backend:
- Python: Foi usado para criar a API, lê os arquivos em .csv, filtra os dados e gera o relatório para o usuário.
- Sqlite3: Versão simplificada de um banco de dados relacional(SQL) para armazenar os dados dos clientes.

#### Contribuições Pessoais

Fui responsável pelo banco de dados em sql e o codigo de conexao com o bd.

#### Hard Skills
- Python - Sei fazer com autonomia
- Sql - Sei fazer com autonomia

#### Soft Skills

- Trabalho em equipe - Colaboração e troca de informações foram essenciais em todas as fases do projeto.
- Aprendizado continuo - Foi necessario aprender varias tecnologias que até então tinha apenas ouvido falar, é essencial manter a mente aberta.

### Em 2020-2
#### Nome do projeto: ShapeTp
#### Empresa parceira: Visiona

O objetivo deste projeto foi desenvolver uma aplicação web do tipo "mini-ETL" que converta arquivos em formato Shapefile para uma tabela existente do banco de dados PostgreSQL/PostGIS e que faça também o caminho inverso, ou seja buscar no banco de dados e devolver ao usuário um arquivo Shapefile. A empresa parceira utilizava uma aplicação paga para tal operação, portanto a necessidade de reduzir custos com um "mini-ETL" open source, que seja pensado para as necessidades especificas desta empresa.

[GIT](https://github.com/IsraelAugusto0110/ShapeTP.git)

- A seguir é apresentada um gif do aplicativo em funcionamento.
- - Convertendo arquivos Shapefile para postgreSql
<img src="https://github.com/IsraelAugusto0110/Trabalho-de-graduacao-1/blob/main/Images/ShapeToPost.gif" width="1000" />

- - Convertendo arquivos postgreSql para Shapefile
<img src="https://github.com/IsraelAugusto0110/Trabalho-de-graduacao-1/blob/main/Images/PostToShape.gif" width="1000" />

#### A equipe era formada por:

- Wesley Dias(Developer)
- Denis Lima(Developer)
- Israel Augusto(Developer)
- Natalia Biscaro(Scrum Master)
- Euclides Resende(PO)
- Sandro de Araujo(Developer)

#### Tecnologias Utilizadas
Backend:
- Java: Utilizada para a criação da API que converte os arquivos e salva no banco.
- PostgreSql: Banco de dados relacional(Sql) capaz de armazenar inclusive dados geometricos, como pontos linhas e poligonos;
- ShapeFile: A extensão .shp é utilizada para armazenar dados geograficos como mapas.
- PgAdmin: Ferramenta para administração de bancos de dados Postgres, com interface de usuário.
Frontend:
- Html e Css: usados para criar a interface de usuários com estilização.
- [Figma](https://www.figma.com/) : utilizado para criar o prototipo das telas.

#### Contribuições Pessoais

Criei as telas utilizando Figma, e codifiquei o frontend.

#### Hard Skills
- PostgreSql - Sei fazer com autonomia
- Html e Css - Sei fazer com autonomia
- Java - Sei fazer com autonomia

#### Soft Skills

- Trabalho em equipe - Colaboração e troca de informações foram essenciais em todas as fases do projeto.
- Aprendizado continuo - Foi necessario aprender varias tecnologias que até então tinha apenas ouvido falar, é essencial manter a mente aberta.


### Em 2021-1
#### Nome do projeto: WebMeeting
#### Empresa parceira: Iacit

O desafio proposto foi de criar um sistema web para criação e gerenciamento de atas de reunião utilizando SQL, NodeJS, React e Javascript. Com as funcionalidades de CRUD de usuários, CRUD das atas, salvar as atas em pdf ou excel e imprimir as atas.

[GIT](https://github.com/IsraelAugusto0110/WebMeeting.git)

- A seguir é apresentada um gif do aplicativo em funcionamento.
<img src="https://github.com/IsraelAugusto0110/Trabalho-de-graduacao-1/blob/main/Images/AppDemo.gif" width="500" />

#### A equipe era formada por:
- Pedro Landin(PO)
- Thiago Canonici(Developer)
- Israel Augusto(Developer)
- Natalia Biscaro(Scrum Master)
- Euclides Resende(Developer)
- Joao Vitor Medeiros(Developer)
- Marcos Yan(Developer)

#### Tecnologias Utilizadas
Backend:
- Node.js: Para criar o servidor da aplicação em javascript e da api que faz as buscas no banco de dados;
- MySql: Banco de dados relacional;
Frontend:
- Html e Css: usados para criar a interface de usuários com estilização.
- [Figma](https://www.figma.com/) : utilizado para criar o prototipo das telas.
- React: Framework em javascript para criar paginas web dianmicas

#### Contribuições Pessoais

Criei a api utilizando javascript e node.js e ajudei na integração entre o frontend e backend. Além disso, modelei e codifiquei o banco de dados.


#### Hard Skills
- Node.js - Sei fazer com autonomia
- React - Sei fazer com autonomia
- Mysql - Sei fazer com autonomia

#### Soft Skills

- Trabalho em equipe - Colaboração e troca de informações foram essenciais em todas as fases do projeto.
- Aprendizado continuo - Foi necessario aprender varias tecnologias que até então tinha apenas ouvido falar, é essencial manter a mente aberta.


### Em 2022-2
#### Nome do projeto: API-5ºSEM
#### Empresa parceira: Fatec ( neste semestre não havia empresa parceira, sendo os professores da Fatec os responsaveis por propor o desafio)

Desenvolver um aplicativo mobile que permita aos cidadaos de um municipio enviar solicitações/reclamações para a secretaria de obras, por exemplo, solicitando a troca de lampadas de um poste ou para informar sobre a coleta de lixo atrasada.

[GIT](https://github.com/IsraelAugusto0110/api-5sem.git)

- A seguir é apresentada um gif do aplicativo em funcionamento.
<img src="https://github.com/IsraelAugusto0110/Trabalho-de-graduacao-1/blob/main/Images/Api5Sem.gif" width="500" />

#### A equipe era formada por:
- Israel Augusto(Developer)


#### Tecnologias Utilizadas
Backend:
- Node.js: Para criar o servidor da aplicação em javascript e da api que faz as buscas no banco de dados;
- MySql: Banco de dados relacional;
Frontend:
- [Figma](https://www.figma.com/) : utilizado para criar o prototipo das telas.
- React Native: Baseado no React, framework JS para desenvolvimento web, o React Native possibilita a criação de aplicações móvel multiplataforma (Android e iOS) utilizando apenas Javascript. Porém, diferente de outros frameworks com esta mesma finalidade (Cordova, por exemplo), todo o código desenvolvido com o React Native é convertido para linguagem nativa do sistema operacional, o que torna o app muito mais fluido.

#### Contribuições Pessoais

Optei por fazer este trabalho sozinho, portanto fui responsavel por todas as tarefas, incluindo o desenho das telas, o banco de dados, a api do backend e programar o frontend.


#### Hard Skills
- Node.js - Sei fazer com autonomia
- React Native - Sei fazer com autonomia
- Mysql - Sei fazer com autonomia

#### Soft Skills

- Trabalho em equipe - Colaboração e troca de informações foram essenciais em todas as fases do projeto.
- Aprendizado continuo - Foi necessario aprender varias tecnologias que até então tinha apenas ouvido falar, é essencial manter a mente aberta.

### Em 2023-1
#### Nome do projeto: Smart Pacer
#### Empresa parceira: Fatec

Em todas as sprints de API há um documento que precisa ser preenchido denominado PACER, com ele os membros da equipe se auto avaliam e avaliam seus Masters, gerando uma nota final. Esse preenchimento era realizado através de um Excel e enviado para o docente responsável pelo API da turma de forma um pouco trabalhosa. Com isso, iremos desenvolver um Software que realiza o cálculo das notas do Pacer, tornando o processo mais prático tanto para o docente quanto para o aluno.

[GIT-Backend](https://github.com/Salitop/SmartPacer.git)
[GIT-Frontend](https://github.com/Salitop/SmartPacer-UI.git)

- A seguir é apresentada um gif do aplicativo em funcionamento.
- <img src="https://github.com/IsraelAugusto0110/Trabalho-de-graduacao-1/blob/main/Images/api6.gif" width="500" />


#### A equipe era formada por:
- Ana Clara Ferreira de Godoy (Product Owner)
- Luiz Miguel Macedo Andre (Master)
- Edryan Matheus dos Santos Maciel (Dev Team)
- Israel Augusto (Dev Team)
- Pedro Sousa Lopes (Dev Team)

#### Tecnologias Utilizadas
Backend:
- Python Flask
- MySql: Banco de dados relacional;
Frontend:
- Html e Css: usados para criar a interface de usuários com estilização.
- [Figma](https://www.figma.com/) : utilizado para criar o prototipo das telas.
- React: Framework em javascript para criar paginas web dianmicas

#### Contribuições Pessoais
No backend fui reponsavel por criar o sistema de login. No frontend criei a tela de login, as telas iniciais do professor e do aluno e tambem a tela de gestão de sprint

#### Hard Skills
- Python Flask - Sei fazer com autonomia
- React Native - Sei fazer com autonomia
- Mysql - Sei fazer com autonomia

#### Soft Skills

- Trabalho em equipe - Colaboração e troca de informações foram essenciais em todas as fases do projeto.
- Aprendizado continuo - Foi necessario aprender varias tecnologias que até então tinha apenas ouvido falar, é essencial manter a mente aberta.

## Meus Principais Conhecimentos
Sendo um aluno da Fatec aprendi muitas tecnologias interessantes, que concerteza serão muito uteis na minha carreira e em futuros projetos, porém as mais interssantes são:
- MySQl: Sistema de banco de dados relacional, utilizado por muitas empresas, grandes e pequenas.
- Python: Linguagem de programação com sintaxe simples e dinamica.
- Java: Permite a criação de apis robustas.
- React Native: Para criar aplicações mobile responsivas e dinamicas. 

## Contatos
* [GIT](https://github.com/IsraelAugusto0110)
* [LinkedIn](https://www.linkedin.com/in/israel-augusto-santos-4651b7197/)



