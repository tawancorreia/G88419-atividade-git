# Como Instalar o Git no Windows

Para instalar o Git no Windows, siga os passos abaixo de forma detalhada:

## 1. Baixar o Instalador do Git

1. Abra o seu navegador e acesse o site oficial do Git: [https://git-scm.com/download/win](https://git-scm.com/download/win).
2. O download do instalador será iniciado automaticamente. Caso não comece imediatamente, clique na opção **"Windows"** para forçar o download.

## 2. Iniciar o Processo de Instalação

1. Depois de concluído o download, localize o arquivo do instalador na pasta **"Downloads"** ou no local onde foi salvo e dê um duplo clique sobre ele para iniciar o processo de instalação.

## 3. Aceitar a Licença de Uso

1. Durante a instalação, o primeiro passo é aceitar a licença de uso. 
2. Leia a licença e clique em **"Next"** para continuar.

## 4. Escolher o Diretório de Instalação

1. O instalador irá sugerir um diretório padrão para instalar o Git (geralmente `C:\Program Files\Git`). 
2. Caso deseje escolher outro local, clique em **"Browse"** e selecione o diretório desejado. 
3. Se não houver necessidade de alterar, clique em **"Next"**.

## 5. Selecionar os Componentes a Serem Instalados

1. O instalador pedirá para selecionar os componentes que deseja instalar. 
2. Recomenda-se deixar as opções padrão, como a **integração ao menu de contexto do Windows Explorer** e a opção de abrir o **Git Bash** diretamente da pasta no Explorer. 
3. Clique em **"Next"** para continuar.

## 6. Escolher o Editor de Texto para o Git

1. Será solicitado que você escolha o editor de texto para ser usado com o Git. 
2. O Git vem configurado para usar o editor **Vim** por padrão. 
3. Se preferir outro editor, como **Notepad++** ou **Visual Studio Code**, você pode selecioná-lo. Caso não tenha preferência, basta clicar em **"Next"**.

## 7. Escolher Como o Git Será Integrado à Linha de Comando

1. O instalador oferece a opção de escolher como o Git será integrado à linha de comando do Windows. 
2. Você pode escolher entre usar o Git **somente no Git Bash** ou também no **Prompt de Comando do Windows**.
3. A recomendação é selecionar **"Use Git from Git Bash only"**, pois oferece uma interface de terminal mais robusta para o Git.

## 8. Definir Como o Git Lida com as Terminações de Linha

1. Será pedida a escolha de como o Git vai lidar com as terminações de linha (end of line) nos arquivos. 
2. A recomendação é deixar a opção **"Checkout Windows-style, commit Unix-style line endings"**, que garante a conversão automática das terminações de linha para o estilo correto dependendo do sistema operacional. 
3. Clique em **"Next"**.

## 9. Configuração do Terminal

1. O instalador também pergunta sobre a configuração do terminal padrão a ser usado pelo Git.
2. A opção recomendada é **"Use MinTTY"**, que fornece um terminal mais avançado.
3. Clique em **"Next"** para continuar.

## 10. Resumo das Configurações e Início da Instalação

1. O instalador exibirá um resumo das configurações escolhidas. 
2. Se estiver tudo certo, clique em **"Install"** para iniciar a instalação. O processo pode levar alguns minutos.

## 11. Finalizar a Instalação

1. Após a instalação ser concluída, clique em **"Finish"** para finalizar o processo.

## 12. Verificar a Instalação

Agora, vamos verificar se o Git foi instalado corretamente:

1. Abra o **Git Bash** (que pode ser encontrado no menu Iniciar ou na área de trabalho).
2. No terminal do **Git Bash**, digite o seguinte comando:

   ```bash
   git --version
