# Handbook do Git - Principais Comandos do Git

## Introdução

O **Git** é um sistema de controle de versão distribuído amplamente utilizado no desenvolvimento de software. Ele permite que os desenvolvedores acompanhem as alterações no código ao longo do tempo, colaborando com outros membros da equipe, e garantindo a integridade e a rastreabilidade do código-fonte.

Neste handbook, vamos cobrir os **principais comandos do Git**, essenciais para começar a usar a ferramenta de forma eficiente. Este guia está dividido em seções que abordam desde a criação de repositórios até a manipulação de branches e commits.

## 1. Inicializando um Repositório

O primeiro passo para começar a trabalhar com Git é **inicializar** um repositório. Um repositório é onde o Git armazena o histórico das alterações feitas no código-fonte.

```bash
git init
Este comando cria um novo repositório Git no diretório atual. Após rodá-lo, você pode começar a adicionar arquivos e comitar alterações.

Este comando cria um subdiretório .git, onde o Git armazenará todos os arquivos e configurações do repositório.

2. Verificando o Status do Repositório
O comando status é usado para verificar o estado atual do repositório. Ele mostra quais arquivos foram alterados, quais ainda não foram adicionados ao staging area, e quais estão prontos para serem comitados.

bash
Copiar
git status
Este comando exibe as mudanças feitas no repositório local, incluindo arquivos modificados e novos arquivos que ainda não foram adicionados ao staging area.

3. Adicionando Arquivos ao Staging Area
Após fazer alterações em arquivos, é necessário adicioná-los ao staging area para que fiquem prontos para o commit. O staging area serve como uma área de preparação antes de registrar as alterações no repositório.

bash
Copiar
git add <arquivo>
Este comando adiciona um arquivo específico ao staging area.

bash
Copiar
git add nome-do-arquivo.txt
bash
Copiar
git add .
Este comando adiciona todos os arquivos modificados ao staging area, ou seja, prepara todos os arquivos para o commit.

4. Realizando um Commit
O commit é a ação de salvar as alterações no repositório. Cada commit deve ser acompanhado por uma mensagem que descreve as mudanças feitas.

bash
Copiar
git commit -m "mensagem"
Este comando cria um commit com as alterações que foram adicionadas ao staging area. A mensagem que você fornecer deve explicar de forma clara e concisa as mudanças feitas.

bash
Copiar
git commit -m "Adiciona nova funcionalidade X"
5. Verificando o Histórico de Commits
Git permite que você visualize o histórico de todos os commits feitos no repositório.

bash
Copiar
git log
Este comando exibe o histórico de commits, mostrando informações como o hash do commit, o autor e a data.

bash
Copiar
git log --oneline
Esta opção exibe o histórico de commits de forma compacta, mostrando cada commit em uma linha.

6. Trabalhando com Branches
Branches (ou ramificações) são uma das funcionalidades mais poderosas do Git. Elas permitem que você desenvolva novos recursos ou corrija bugs em paralelo ao desenvolvimento principal.

bash
Copiar
git branch <nome-da-branch>
Este comando cria uma nova branch. Porém, ao criar uma branch com este comando, você não será automaticamente transferido para ela.

bash
Copiar
git branch nova-branch
bash
Copiar
git checkout <nome-da-branch>
Este comando muda para a branch especificada.

bash
Copiar
git checkout nova-branch
bash
Copiar
git checkout -b <nome-da-branch>
Este comando cria uma nova branch e já muda para ela.

bash
Copiar
git checkout -b nova-branch
7. Realizando Merge de Branches
Uma vez que você tenha feito alterações em uma branch e esteja pronto para integrar essas mudanças de volta à branch principal, você pode usar o merge.

bash
Copiar
git merge <nome-da-branch>
Este comando faz o merge (integração) da branch especificada à branch atual.

bash
Copiar
git merge nova-branch
8. Interagindo com Repositórios Remotos
Git permite que você trabalhe com repositórios remotos (como GitHub, GitLab, Bitbucket), onde seu código é armazenado centralmente e pode ser compartilhado com outras pessoas.

bash
Copiar
git clone <url-do-repositório>
Este comando clona um repositório remoto para o seu computador local, criando uma cópia completa do projeto.

bash
Copiar
git clone https://github.com/usuario/repositorio.git
bash
Copiar
git pull
Este comando baixa e integra as últimas alterações de um repositório remoto para o seu repositório local.

bash
Copiar
git pull origin main
bash
Copiar
git push
Este comando envia as alterações locais para o repositório remoto, atualizando-o com seus commits.

bash
Copiar
git push origin main
9. Excluindo Arquivos ou Commits
Às vezes é necessário excluir arquivos do repositório ou reverter commits.

bash
Copiar
git rm <arquivo>
Este comando remove um arquivo do repositório.

bash
Copiar
git rm nome-do-arquivo.txt
bash
Copiar
git reset --hard <commit>
Este comando faz o reset do repositório para um commit específico, descartando todas as alterações posteriores.

bash
Copiar
git reset --hard abc1234
10. Revertendo Commits
Se você cometeu um erro em um commit, pode revertê-lo criando um novo commit que desfaz as alterações.

bash
Copiar
git revert <commit>
Este comando cria um novo commit que reverte as alterações feitas por um commit anterior.

bash
Copiar
git revert abc1234
