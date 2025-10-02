## Começando

Bem-vindo ao mundo Java do VS Code. Aqui está um guia para ajudar você a começar a escrever código Java no Visual Studio Code.

## Estrutura de Pastas

O espaço de trabalho contém duas pastas por padrão, onde:

- `src`: a pasta para manter os códigos-fonte
- `lib`: a pasta para manter as dependências

Enquanto isso, os arquivos de saída compilados serão gerados na pasta `bin` por padrão.

> Se você quiser personalizar a estrutura de pastas, abra `.vscode/settings.json` e atualize as configurações relacionadas lá.

## Gerenciamento de Dependências

A visualização `PROJETOS JAVA` permite que você gerencie suas dependências. Mais detalhes podem ser encontrados [aqui](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).


## Terminal.

Compile o arquivo do diretório src e coloque o .class em bin (isso é o padrão que você já tem na pasta bin):

javac -d ..\bin Exemplo.java


-d ..\bin indica que o arquivo .class será gerado na pasta bin que está um nível acima da pasta src.

2️⃣ Verifique o .class:

ls ..\bin


Você deve ver:

Exemplo.class


3️⃣ Execute a classe a partir do diretório java (não src), especificando o classpath bin:

java -cp bin Exemplo


Saída esperada:

feliz!