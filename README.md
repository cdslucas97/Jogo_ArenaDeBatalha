ARENA DE BATALHA

CONTEXTO: <br>
Você foi contratado para desenvolver a base de um jogo de batalha simples, onde personagens enfrentam inimigos em um sistema de turnos. Seu objetivo é criar um sistema organizado e bem estruturado utilizando os princípios da Programação Orientada a Objetos.

OBJETIVOS: <br>
Este PBL tem como foco o desenvolvimento das seguintes habilidades: <br>
  • Definição e uso de classes e construtores; <br>
  • Aplicação do encapsulamento para proteger os atributos das classes; <br>
  • Uso de coleção de objetos (ArrayList) para armazenar personagens e inimigos; <br>
  • Implementação da interação entre objetos para gerenciar combates em turnos. <br>

-------------------------------------------------------------------------------------------------------------------------------

DESCRIÇÃO DO PROBLEMA:

Seu jogo contará com três elementos principais: <br> 
  • Personagem: Um herói controlado pelo jogador, com atributos como nome, vida, ataque e defesa; <br> 
  • Inimigo: Criaturas que o personagem enfrentará, com os mesmos atributos; <br> 
  • Batalha: Responsável por gerenciar os turnos, alternando ataques entre o personagem e o inimigo até que um deles fique sem vida. <br> 

O jogo deve iniciar com um personagem e um inimigo, escolhidos de uma lista pré-definida. Em cada turno:
1. O personagem ataca o inimigo, causando dano baseado no seu valor de ataque menos a defesa do inimigo;
2. Se o inimigo ainda estiver vivo, ele contra-ataca seguindo a mesma lógica;
3. O jogo continua até que um dos dois chegue a 0 de vida.

-------------------------------------------------------------------------------------------------------------------------------

REQUISITOS TÉCNICOS:

1. Classes e Construtores
Crie pelo menos as seguintes classes: <br>
  • Personagem: atributos nome, vida, ataque, defesa; <br>
  • Inimigo: atributos nome, vida, ataque, defesa; <br>
  • Batalha: gerencia o combate entre um Personagem e um Inimigo. <br>
Cada classe deve possuir um construtor para inicializar os atributos. <br>

2. Encapsulamento: <br>
• Todos os atributos devem ser private; <br>
• Utilize getters e setters para acessar e modificar valores quando necessário. <br>

3. Coleção de Objetos: <br>
• Crie uma ArrayList<Personagem> com diferentes personagens disponíveis; <br>
• Crie uma ArrayList<Inimigo> com diferentes inimigos; <br>
• O jogo deve permitir escolher um personagem e um inimigo para a batalha. <br>

4. Interação entre Objetos: <br>
• A classe Batalha deve ter um método para iniciar o combate e alternar os turnos entre personagem e inimigo; <br>
• Exiba mensagens informando o que está acontecendo a cada turno (exemplo: "Personagem X atacou o inimigo Y causando Z de dano"); <br>
• Ao final, exiba quem venceu a batalha. <br>
