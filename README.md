<h1>🐍 Python Starter: Pasta Básica</h1>

Este repositório contém os fundamentos essenciais da linguagem Python. É o "arroz com feijão" (ou a massa básica) para quem está começando a programar.

<h2>🚀 Comandos Básicos</h2>
Os primeiros passos para interagir com o interpretador:

print(): Exibe informações no console.

input(): Recebe dados do usuário.

type(): Verifica o tipo de dado de uma variável.

len(): Retorna o tamanho (comprimento) de um objeto.

📋 Manipulação de Listas
As listas são coleções mutáveis e ordenadas. Aqui estão os métodos que você mais vai usar:


<h1>🛠️ Configuração de Ambiente Virtual (venv)</h1>

Este guia prático ensina como criar, ativar e gerenciar um ambiente virtual para projetos Python.

📋 Por que usar?

O venv permite que você instale dependências específicas para este projeto sem afetar o Python global do seu sistema, evitando o famoso erro: "Mas na minha máquina funciona!".

🚀 Passo a Passo

<h3>1. Criar o ambiente virtual</h3>
  
Abra o terminal na pasta raiz do projeto eexecute:
Bash

# No Windows, macOS ou Linux
python -m venv .venv

Nota: O nome .venv é o padrão da comunidade, mas você pode escolher outro.


<h3>2. Ativar o ambienteA ativação depende do seu sistema operacional:</h3>

   Sistema OperacionalComando no TerminalWindows (Command Prompt).venv\Scripts\activat

   Windows (PowerShell).\venv\Scripts\Activate.ps1

   macOS / Linuxsource .venv/bin/activate


 Ao ativar, você verá o nome (.venv) aparecer antes do cursor no terminal.


<h3> 3. Instalar dependênciasCom o ambiente ativo, instale os pacotes necessários:Bashpip install -r requirements.txt</h3>
      
<h3> 4. Desativar o ambienteQuando terminar de trabalhar, basta digitar:</h3>
  
  Bash
  deactivate

     
⚠️ Dica de Ouro: .gitignoreNunca envie a pasta do seu ambiente virtual para o GitHub. Certifique-se de que seu arquivo .gitignore contenha a linha:Plaintext.venv/
