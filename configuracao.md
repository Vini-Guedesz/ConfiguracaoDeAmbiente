# Documentação de Ambiente de Trabalho

## Sumário

1.  [Java Development Kit (JDK) 21](#1-java-development-kit-jdk-21)
2.  [IntelliJ IDEA Community Edition](#2-intellij-idea-community-edition)
3.  [Visual Studio Code (VS Code)](#3-visual-studio-code-vs-code)
4.  [Node.js e npm](#4-nodejs-e-npm)
5.  [Vue.js](#5-vuejs)

---

### 1. Java Development Kit (JDK) 21

O JDK é essencial para o desenvolvimento de aplicações em Java.

#### 1.1. Download

* Acesse a página oficial de downloads da Oracle: [https://www.oracle.com/java/technologies/downloads/#java21-windows](https://www.oracle.com/java/technologies/downloads/#java21-windows)
* Na seção "Java 21", selecione a aba "Windows".
* Clique no link de download para o "x64 Installer".

#### 1.2. Instalação

* Execute o arquivo `.exe` que você baixou.
* Siga as instruções do assistente de instalação. É recomendado manter o diretório de instalação padrão.
* Aguarde a conclusão do processo.

#### 1.3. Verificação

* Abra o Prompt de Comando (CMD) ou PowerShell.
* Execute o seguinte comando para verificar a versão do Java:

    ```bash
    java -version
    ```

* A saída deve indicar a versão "21" do Java.

---

### 2. IntelliJ IDEA Community Edition

Uma IDE (Ambiente de Desenvolvimento Integrado) robusta para desenvolvimento em Java.

#### 2.1. Download

* Acesse a página oficial de downloads do IntelliJ IDEA: [https://www.jetbrains.com/pt-br/idea/download/](https://www.jetbrains.com/pt-br/idea/download/)
* Certifique-se de que a versão "Community" está selecionada e clique em "Baixar".

#### 2.2. Instalação

* Execute o instalador baixado.
* Siga as instruções do assistente. Você pode personalizar as opções de instalação, como a criação de um atalho na área de trabalho e associações de arquivos.
* Prossiga com a instalação.

---

### 3. Visual Studio Code (VS Code)

Um editor de código-fonte leve e poderoso, ideal para desenvolvimento front-end.

#### 3.1. Download

* Acesse o site oficial do VS Code: [https://code.visualstudio.com/](https://code.visualstudio.com/)
* O site detectará automaticamente o seu sistema operacional. Clique no botão de download para obter o instalador.

#### 3.2. Instalação

* Execute o arquivo de instalação.
* Aceite o contrato de licença e clique em "Próximo".
* É recomendado marcar as opções "Adicionar 'Abrir com Code' ao menu de contexto de arquivo do Windows Explorer" e "Adicionar 'Abrir com Code' ao menu de contexto de diretório do Windows Explorer" para facilitar o uso.
* Conclua a instalação.

---

### 4. Node.js e npm

Node.js é um ambiente de execução JavaScript. O npm (Node Package Manager) é o seu gerenciador de pacotes, utilizado para instalar bibliotecas e frameworks como o Vue.js.

#### 4.1. Download

* Acesse a página oficial de downloads do Node.js: [https://nodejs.org/pt/download/](https://nodejs.org/pt/download/)
* Faça o download da versão **v22.17.1 LTS** (Long-Term Support), que é a recomendada para a maioria dos usuários por sua estabilidade.

#### 4.2. Instalação

* Execute o instalador `.msi` baixado.
* Siga as instruções do assistente de instalação. Mantenha as configurações padrão, que incluem a instalação do npm.
* Aguarde a finalização do processo.

#### 4.3. Verificação

* Abra um novo terminal (CMD ou PowerShell).
* Verifique a versão do Node.js com o comando:

    ```bash
    node -v
    ```

* Verifique a versão do npm com o comando:

    ```bash
    npm -v
    ```

---

### 5. Vue.js

Um framework progressivo para a construção de interfaces de usuário. A maneira recomendada de iniciar um novo projeto Vue é através da ferramenta de linha de comando `create-vue`.

#### 5.1. Criação de um Projeto Vue

* Abra o seu terminal (CMD, PowerShell ou o terminal integrado do VS Code).
* Navegue até o diretório onde deseja criar seu projeto.
* Execute o seguinte comando para iniciar um novo projeto Vue. Este comando instalará e executará `create-vue`, a ferramenta oficial para criação de projetos Vue.

    ```bash
    npm create vue@latest
    ```

* Você será solicitado a responder a algumas perguntas para configurar o seu projeto (por exemplo, nome do projeto, se deseja usar TypeScript, suporte a JSX, etc.). Selecione as opções que melhor se adequam às suas necessidades.

#### 5.2. Executando o Projeto

* Após a criação do projeto, navegue para o diretório do projeto:

    ```bash
    cd <nome-do-seu-projeto>
    ```

* Instale as dependências do projeto:

    ```bash
    npm install
    ```

* Inicie o servidor de desenvolvimento:

    ```bash
    npm run dev
    ```

* Abra o seu navegador e acesse o endereço local fornecido no terminal (geralmente `http://localhost:5173`). Você deverá ver a página inicial da sua nova aplicação Vue.
