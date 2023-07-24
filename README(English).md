# <p align="center">Project: A fuga de Filó </p>

## 1) Team Members of `Team 7`:
<br>

- Cleandson Lopes de Albuquerque 
- Dayane Camile Bezerra de Lima
- José Ronaldo de Souza Silva
- Luiz Henrique Brito
- Mariana Marinho da Silva Andrade
- Vitória Beatriz Alexandre Silva 

<br>
     
## 2) Git Repository Link
  
   https://github.com/Dev-JoseRonaldo/projeto-p1-equipe7

<br>

## 3) How to run the project

### Prerequisites

Before downloading the project, make sure you have the following tools installed on your machine:

* [Python 3.9 or higher](https://www.python.org/downloads/)
* [Pygame](https://www.pygame.org/news)

### Then:

```bash
# Clone the repository
$ git clone https://github.com/Dev-JoseRonaldo/projeto-p1-equipe7.git

# Open the project
Open the cloned folder in your favorite code editor.

# Start the game
Run the main.py file present in the root of the repository.

# Your code editor will run the game in a new window.
```

<br>

## 4) Code organization;
<br>
For code organization, we followed a structure with the main.py file, README.md file, and folders. The main.py file was used as the main file of the code, with all the elements and functionalities being called within it.

<br>
<br>

The main.py file is structured as follows:


    1. Imports

    2. Pygame general screen parameters

    3. Variables for screens to be opened

    4. Menu screen variables

    5. Game over screen variables

    6. Lives

    7. Powerups

    8. While loop running the game



The folders store different classes and images. Inside the "assets" folder, we also have subfolders where we have the classes of the screens ("screens"), functionality/POO classes ("scripts"), and images ("sprites").

<br>

## 5) Tools, libraries, frameworks used with their respective justifications for use;

- `pygame`: We used pygame because it provides various integrated tools and resources for creating 2D games. In addition to its ease of use for beginners in programming game development.

- `time`: We used the time library for functions such as measuring the start time of the game and storing it in a variable for later use, controlling the screen refresh rate, and measuring the time since the last update to control the time interval between updates of the player's sprite.

- `random`: The random library was used to randomly generate the items to be collected by the player, as well as the items the player must avoid.

- `scrum and kanban`: We used these agile methodologies for team management and monitoring. We had 5 sprints of 4 days each.

<br>

## 6) Division of work within the group (who did what);

`Luiz`: Animation class (Animacao), text class (text), and report.

`Dayane`: Game Over class, Menu class, Button class, and group slides.

`Ronaldo`: Enemy and powerup spawn system, parallax system, powerup collection system, organization and control of the GitHub repository and team code.

`Cleandson`: Collision systems, life systems, and background art.

`Mariana`: User movement system, scoring system, difficulty increase system, organization of Notion.

`Vitória`: Character art, element art, game sounds, and report.

 <br>   

## 7) Concepts presented during the course and used in the project (indicating where they were used);

Object-oriented programming, conditionals, loops, functions, lists, dictionaries.

We used OOP and its three main concepts (encapsulation, inheritance, and polymorphism) to define important entities of our game, such as the Player, Enemies, Powerups, etc. This way, we were able to instantiate various elements with similar characteristics and actions. Knowledge of functions was also essential for constructing the methods of these classes, where we always tried to use functions to modify class properties (encapsulation).
Conditionals and loops were used in various parts of the code to limit certain functionalities to specific situations. In general, they were essential structures for building the game logic.

<br>

## 8) Challenges and errors faced during the project and lessons learned.

- Lack of knowledge of git/github: We faced some difficulties in using and understanding git commands. However, with practice, everything became easier throughout the project. So, practice is fundamental to solidify these commands.

- Working in a team: As it was a new experience for most of the group, it was something new and a bit challenging for us, such as having to wait for someone to finish in order to start your task and also respecting each person's work and

- Working with very short sprints (around 4 days) creates immediate delivery pressure, combined with other academic activities, making it quite challenging to succeed in sprint deliveries.

<br>

## 9) Qual foi o maior erro cometido durante o projeto? Como vocês lidaram com ele? 

A maior falha foi na organização e distribuição de tarefas, considerando o tempo disponível para desenvolver o projeto e a quantidade de tarefas a serem realizadas pelo grupo. Isso resultou em atrasos no início do projeto. Tentamos distribuir as tarefas de acordo com a disponibilidade de cada membro e nos ajudamos mutuamente quando alguma tarefa ficava pendente.

<br>

## 10) Qual foi o maior desafio enfrentado durante o projeto? Como vocês lidaram com ele? 

O maior desafio foi estruturar o código utilizando programação orientada a objetos (POO). Assistimos a vários vídeos no YouTube para obter orientações sobre a refatoração do código e também mantivemos uma comunicação constante entre nós para implementar o código da melhor maneira possível. 

<br>        

## 11) Quais as lições aprendidas durante o projeto? 

- É fundamental planejar o projeto com antecedência. Dividir o trabalho em sprints e tarefas para cada membro foi essencial para concluir o projeto dentro do prazo determinado.  

- A comunicação é indispensável em trabalhos em equipe e projetos como esse. Portanto, nos comunicamos diariamente para acompanhar o progresso do projeto e garantir que as tarefas das sprints fossem concluídas no prazo.

- Todos têm algo a ensinar e algo a aprender. Durante a construção do jogo, houve uma troca significativa de conhecimento sobre as ferramentas utilizadas no projeto.

- Aprender a identificar e corrigir erros de código é crucial para o desenvolvimento do jogo e o progresso do projeto.

- É importante ouvir as opiniões dos outros e implementá-las no código, a fim de melhorar o jogo e proporcionar a melhor experiência possível ao usuário final.

- Colaborar com outros programadores, compartilhando códigos e ideias, desenvolve habilidades fundamentais para os desenvolvedores.

- Ter paciência e persistência é essencial para superar obstáculos e dificuldades que possam surgir durante o processo de criação do projeto.

- O verdadeiro trabalho em equipe foi o mais importante de todos, pois sem programarmos juntos, o projeto não teria sido bem-sucedido.

 <br>
 <br>

## 12) Screenshots of the system functioning to compose the project gallery
<br>

### <p align="center">Menu Screen </p>
<p align="center">
  <img alt="Banner menu" src="https://res.cloudinary.com/devjoseronaldo/image/upload/v1683518794/jogo-p1/menu-banner_khqzhx.png" width="80%">
</p>

<br>
<br>

### <p align="center">Game Screen </p>
<p align="center">
  <img alt="Banner game" src="https://res.cloudinary.com/devjoseronaldo/image/upload/v1683518793/jogo-p1/game-banner_ojchiy.png" width="80%">
</p>

<br>
<br>

### <p align="center">Game Over Screen </p>
<p align="center">
  <img alt="Banner gameover" src="https://res.cloudinary.com/devjoseronaldo/image/upload/v1683558030/jogo-p1/gameover-banner_k9cv7w.png" width="80%">
</p>
