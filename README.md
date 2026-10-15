# Estrutura_de_relatorio

Estrutura em LaTeX para a criação padronizada e (quase) seguindo a normal abnt.

## Como utilizar essa estrutura

Esse tutorial assume que o VScode esteja instalado em seu computador. Se não tiver esse software instalado, instale-o agora.

O tutorial de uso será separado em passos, cada passo será uma macro-instrução que poderá ser quebrada em instruções menores.

### 1. Instalação do compilador de LaTeX

Para que o documento seja gerado em pdf, um compilador é necessário. Indico o MiKTeX como compilador para quem esteja usando o Windows.
Para instalar esse compilador siga os passos abaixo:

- Abra o prompt de comando;
- Execute o comando a baixo:

    ```bash
    winget install --id MiKTeX.MiKTeX
    ```

- Siga o processo de instalação;
- Para garantir que o compilador tenha sido intalado, digite no prompt de comando:

    ```bash
    miktex --version  
    ```

    Uma mensagem de informação sobre o compilador deve aparecer indicando que a instalção foi bem sucedida.

### 2. Instalação do Strawberry Perl

Alguns arquivos do compilador são escritos em Perl, portanto, para que a compilação ocorra sem erros, precisamos instalar esse ambiente voltado para Perl.

Para instalar esse ambiente vá até o site [Strawberry Perl](https://strawberryperl.com/) baixe e instale o ambiente conforme o instalador manda.

### 3. configuração do VScode

Para garantir um abiente adequado para a criação de documentos com o LaTeX, é preciso instalar uma extensão para o VScode.
O nome da extensão é `LaTeX Workshop`. Procure por esse nome dentro da aba de extensões do vscode e a instale.

## Ambiente preparado

Após preparar o ambiente, basta apenas clona esse repositório no seu computador, achar um botão verde no canto superior direito da tela e clicar para compilar o arquivo pela primeira vez. Após a primeira vez compilado, o arquivo em pdf é atualizado toda vez que uma alteração no código é feita.

## Dúvidas

Em caso de dúvidas mande um email para [araujojv04@yahoo.com](mailto:araujojv04@yahoo.com?subject=Ajuda%20com%20o%20repositorio%20para%20relatorios)

#### Created by file_manager
