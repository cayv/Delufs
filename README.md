# Delufs

Este repositório existe com o propósito de proporcionar uma introdução aos alunos do Departamento de Engenharia Elétrica da Universidade Federal de Sergipe à linguagem Julia.

# Instalação

Para ter uma boa experiência de desenvolvimento, é importante fazer o setup não só da linguagem, mas também de algumas ferramentas que auxiliam o programador, aumentando a sua produtividade. Este tutorial assume que o usuário está num computador com sistema operacional Windows 10 ou superior.

Instaleremos os seguintes programas:

- Julia.

- Windows Terminal: O novo terminal oficial do Windows. Versões mais modernas do Windows já vêm com o Terminal instalado por padrão. Ele nos permite iniciar uma sessão Julia com apenas dois cliques.

- Visual Studio Code: O VS Code é o editor de texto oficial da linguagem Julia. Você pode utilizar qualquer editor de texto de sua preferência, mas o Language Server oficial da linguagem Julia é desenvolvido com foco no VS Code, permitindo uma integração muito maior do que com outros editores.

## Instalação com `winget`

Ao invés de utilizar o processo tradicional de baixar e executar os instaladores de cada programa, podemos instalá-los com o `winget`, o Cliente Gerenciador de Pacotes oficial do Windows, lançado pela Microsoft em 2021. O `winget` já deve estar no seu sistema caso ele tenha sido recentemente atualizado.

Para saber se o `winget` está instalado, abra o Prompt de Comando (pressione `Windows + R` para abrir a janela de execução, digite `cmd` e aperte `Enter`). No prompt, digite:

    where winget

Caso o `winget` esteja instalado, o comando irá retornar a localização do programa (ex: `C:\Users\usuario\AppData\Local\Microsoft\WindowsApps\winget.exe`).

Caso não esteja, um erro deve aparecer informando que não foi possível localizar o programa (ex: `INFO: Could not find files for the given pattern(s).`). Você pode obter o `winget` instalando o [App Installer](https://www.microsoft.com/store/productId/9NBLGGH4NNS1) na Microsoft Store.

Uma vez que o `winget` esteja presente, podemos dar início à instalação dos programas. Para instalar um programa com o `winget`, basta digitar o seguinte comando num terminal da sua preferência:

    winget install -e --id programa

Substituindo `programa` pelo identificador do programa que deseja instalar. No caso, iremos executar os seguintes comandos, uma linha de cada vez:

    winget install -e --id Julialang.Julia

    winget install -e --id Microsoft.WindowsTerminal

    winget install -e --id Microsoft.VisualStudioCode

Assim como as instalações utilizando instaladores tradicionais, alguns programas exigem privilégios de administrador para que a instalação seja finalizada com sucesso. Basta confirmar o prompt quando for requisitado.

## Download de instaladores

Caso não se sinta confortável utilizando uma interface de linhas de comando, você pode baixar os instaladores dos programas nos seguintes links:

- Julia: Download do instalador no [site oficial](https://julialang.org/downloads/);

- Windows Terminal: instalação direta através da [Microsoft Store](https://www.microsoft.com/store/productId/9N0DX20HK701) (recomendado) ou instaladores de versões específicas no [Github](https://github.com/microsoft/terminal/releases);

- Visual Studio Code: Download do instalador no [site oficial](https://code.visualstudio.com/Download) (recomendado) ou instalação direta através da Microsoft Store.

