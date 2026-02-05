# Cyber Chess System v1.0

## Sobre o Projeto
Este projeto é uma releitura do clássico jogo de xadrez, desenvolvido em Java e executado via console. A aplicação utiliza conceitos avançados de Programação Orientada a Objetos para implementar a lógica completa do jogo, mas com uma camada visual e narrativa customizada inspirada na estética Cyberpunk.

Diferente do xadrez tradicional, esta versão situa o jogador em um conflito digital, substituindo as peças clássicas por facções futuristas e utilizando códigos ANSI para criar uma interface de usuário em cores Neon (Ciano e Roxo) diretamente no terminal.

## A Temática: Netrunners vs Corporação
O tabuleiro representa o ciberespaço, onde duas forças colidem pelo controle do sistema:

* **NETRUNNERS (Peças Brancas / Ciano):** Hackers rebeldes lutando pela liberdade da informação.
* **CORPORAÇÃO (Peças Pretas / Roxo):** O sistema opressor e suas defesas automatizadas (AI Core).

## Funcionalidades Técnicas
* **Interface Visual Customizada:** Renderização do tabuleiro utilizando cores ANSI de alto contraste (Ciano Neon e Roxo) sobre fundo escuro.
* **Highlight de Movimento:** Indicação visual de movimentos possíveis com fundo verde estilo "Matrix".
* **Lógica Completa de Xadrez:**
    * Movimentação e Captura de peças.
    * Validação de jogadas (impede movimentos ilegais).
    * Detecção de Xeque e Xeque-mate.
    * Jogadas Especiais: Roque, En Passant e Promoção.
* **Sistema de Turnos:** Alternância controlada entre as facções "Netrunner" e "Corporação".

## Tecnologias Utilizadas
* Java (JDK 11+)
* Conceitos de POO: Encapsulamento, Herança, Polimorfismo e Tratamento de Exceções.

## Como Executar

### Pré-requisitos
* Java JDK 11 ou superior.
* Terminal com suporte a cores ANSI (Linux Terminal, Git Bash ou Windows Terminal).

### Passo a Passo
1.  Clone o repositório:
    ```bash
    git clone [https://github.com/jotadevs17/chess-system-java.git](https://github.com/jotadevs17/chess-system-java.git)
    ```
2.  Acesse a pasta do projeto:
    ```bash
    cd chess-system-java
    ```
3.  Compile o código fonte:
    ```bash
    javac -d bin -sourcepath src src/application/Program.java
    ```
4.  Execute a aplicação:
    ```bash
    java -cp bin application.Program
    ```

## Autor e Créditos
**Desenvolvedor:** João Pedro

**Nota de Estudo:**
A arquitetura base deste sistema (camadas de xadrez e tabuleiro) foi desenvolvida seguindo o curso de Java do professor Nélio Alves. Sobre essa base sólida, implementei a refatoração completa da camada de Interface de Usuário (UI), alterando a identidade visual, paleta de cores e a lógica de apresentação para criar a experiência "Cyber Chess".
