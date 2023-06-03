# Instalação Cordova

Obs: Lembrar que o node deve estar instalado na máquina.

## Comando de instalação do cordova:

> > > npm install -g cordova
> > > Obs: Pode ser solicitado o update de uma versão mais recente do npm.
> > > No meu caso solicitou o update para versão 9.6.7 do seguinte modo:
> > > npm install -g npm@9.6.7

## instalação do JAVA JDK

- Baixar o executavel compartilhado no Drive;
- Caminho do arquivo instalado: C:\Program Files\Java\jdk-11.0.4

## Editar as variáveis de ambiente:

- Nas variáveis do sistema, clicar em novo;
- Primeiro campo: JAVA_HOME
- Segundo Campo: C:\Program Files\Java\jdk-11.0.14
- Após isso, procurar o Path nas variáveis do sistema e clicar em editar;
- Inserir o caminho do diretório bin do JDK: C:\Program Files\Java\jdk-11.0.14\bin

## Instalação do gradle:

- No diretório C, criar um diretório com o nome Gradle;
- Baixar o arquivo zipado compartilhado no Drive;
- Inserir e extrair o arquivo zipado no diretório Gradle;

## Editar as variáveis de ambiente:

- Nas variáveis do sistema, clicar em novo;
- Primeiro campo: gradle (minusculo msm)
- Segundo Campo: C:\Gradle\gradle-7.5.1
- Após isso, procurar o Path nas variáveis do sistema e clicar em editar;
- Inserir o caminho do diretório bin do JDK: C:\Gradle\gradle-7.5.1\bin;

## Baixar o android studio:

Obs: O android studio não será utilizado, baixamos o programa apenas para configurar o sdk manager;

- Na tela inicial ao abrir o Android Studio, clicar em More Actions;
- Em disco local C, criar diretório chamado Android e, nela, um subdiretorio chamado sdk;
- Clicar em edit, na tela de configuração do sdk manager, inserir o caminho do diretorio sdk criado no campo presente no rodapé da página: C:\Android\sdk;
- Aceitar as licenças do Android Studio e next para instalação do pacote do android 33;
- Instalar a versão 30 do sdk, android 11, que é a versão que está sendo utilizada pelo cordova. Para isso, desmarcar a versão 33 e baixar apenas a versão 30;
- Depois ir em SDK tools, marcar apenas a versão 30.0.3 e clicar em apply;
- Processo finalizado, fechar o Android Studio.

## Editar as variáveis de ambiente:

- Nas variáveis do sistema, clicar em novo;
- Primeiro campo: ANDROID_HOME
- Segundo Campo: C:\Android\sdk
- Após isso, procurar o Path nas variáveis do sistema e clicar em editar;
- Inserir os seguintes caminhos:
  -> C:\Android\sdk\platform-tools
  -> C:\Android\sdk\build-tools
