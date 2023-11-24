

## Rede Social em Java

Este é um simples programa em Java que simula uma rede social
O programa permite ao usuário cadastrar, logar, adicionar amigos, enviar e receber mensagens.

## Menu
1. [Como Executar](#como-executar)
1. [Funcionalidades do Programa](#funcionalidades-do-programa)
1. [Menu Via Terminal](#menu-via-terminal-lista-tarefas)
1. [Telas](#telas-da-aplicação)

```markdown
## Requisitos

- JDK (Java Development Kit): versão 17
- Git: version 2.40.0.windows.1
- Bibliotecas padrão do Java: Scanner, Swing.
- PGAdmin4 instalado na máquina.
```
## Como Executar

1. Clone o repositório:

   ```shell
   git clone https://github.com/carlos-fernandino/RedeSocial.git
   ```

2. Acesse o diretório do projeto:

   ```shell
   cd .\RedeSocial\src\
   ```

3. Utilize o Java para executar o arquivo:
   ## Via console
   ```shell
   java .\Main.java
   ```
   ou
   ## Via GUI
      ```shell
   java .\RedeSocialGUI.java
   ```
4. Instale o PGAdmin4 na máquina:

   ```shell
   https://www.pgadmin.org/download/
   ````
5. Dentro do projeto, busque por "Arquivo"

   5.1 :
   Acesse a "Estrutura de Projeto", busque por "Modulos" e o acesse.
   
   5.2 :
   Dentro de "Modulos" clique no "+" e selecione o arquivo .jar do seu PGAdmin4.
   Em seguida, selecione-o e clique em "Aplicar".


6. Na classe Sistema:

   6.1 :
   Personalise a URL, o USER e o PASS com a porta local alocada para o banco, usuário e senha
   destinados a esses campos em sua máquina, respectivamente.


7. Rode a classe "RedeSocialGUI.java"

## Funcionalidades do programa:

- **Cadastrar Usuario**: O usuário cadastra com nome, email e senha. E salva seu cadastro no banco de dados

- **Login**: O usuário acessa as funcionalidades do sistema.

- **Adicionar Amigo**: Adiciona um usuário a lista de amigos.

- **Consultar Amigos**: Exibe a lista de amigos.

- **Enviar Mensagem**: Enviar mensagem a um amigo.

- **Visualizar Mensagens Enviadas**: Exibe a lista de mensagens enviadas

- **Visualizar Mensagens Recebidas**: Exibe a lista de mensagens recebidas

- **LogOut**: Usuário retorna a tela inicial


## Menu via terminal Rede Social:

LogOFF

===== Mini Simulador de Rede Social =====
1. Cadastrar Usuário
2. Login
0. Sair
   Escolha uma opção:

LogON

===== Mini Simulador de Rede Social =====
Bem-vindo, Carlos!
1. Adicionar Amigo
2. Consultar Amigos
3. Enviar Mensagem
4. Visualizar Mensagens Enviadas
5. Visualizar Mensagens Recebidas
6. Logout
0. Sair
   Escolha uma opção:
## Telas da aplicação

**Tela Inicial**

<img src="prints/
