Criar uma conta no GitHub: Acesse github.com e crie uma conta, caso ainda não tenha.

Instalar o Git: Se ainda não tiver, instale o Git na sua máquina:

Windows: Baixe em git-scm.com.
Mac: Use o terminal com git --version.
Linux: Instale via gerenciador de pacotes.
Configurar o Git: No terminal, defina seu nome de usuário e e-mail:

bash
Copiar
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
Criar um repositório no GitHub:

No GitHub, clique no ícone de "+" e selecione "New repository".
Defina o nome e visibilidade do repositório.
Crie o repositório.
Subir seu código para o GitHub:

No diretório do seu projeto, execute:
bash
Copiar
git init
git add .
git commit -m "Primeiro commit"
Conecte o repositório local ao GitHub:
bash
Copiar
git remote add origin https://github.com/usuario/repo.git
Envie o código para o GitHub:
bash
Copiar
git push -u origin main
Confirmar no GitHub: Verifique o repositório no GitHub para garantir que os arquivos foram enviados.
