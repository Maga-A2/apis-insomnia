<h2 align="center">APIs Insomnia</h2>

#### 1 - Instalação

Baixe o insomnia na sua máquina e instale os plugins listados abaixo. 

> Para instalar os plugins acesse o insomnia, vá em configurações e na aba de plugins informe o nome do plugin.

1. insomnia-plugin-faker

#### 2 - Importar Projeto

> ⚠ Se você já tiver o projeto no Insomnia e ele possuir alterações, lembre-se que ao reimportar, requisições e pastas **que já existiam** serão resetados para as definições do arquivo sendo importado, em outras palavras, você perderá suas atualizações; Portanto, exporte o projeto para um outro arquivo ou crie um branch.

#### 2.1 - Utilizando o botão

> ⚠ Em alguns casos por motivos desconhecidos o botão não consegue reimportar o projeto.

Nome da API    | Botão de import
-------------- | ---------------
Magazord V1/V2 | <a href="https://insomnia.rest/run/?label=MagaZord%20API%20V1%2FV2&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fmagazord-plataforma%2Fapis-insomnia%2Fmain%2FMagaZord%2Fmagazord-api-v1-v2.yaml%3Ftoken%3DAQ52OBU5DRKH73VKL2NPPB3BDVYVU" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>

#### 2.2 - Manualmente
1. Clone este repositório em algum diretório de sua preferência; 
 
> Se você já possui este repositório versionado localmente lembre-se de atualizá-lo;
 
2. Acesse as configurações do Insomnia e vá na aba data;
3. Clique no botão import e selecione o arquivo `.yaml` da API que você deseja testar;

#### 3 - Alterando Senhas

Na primeira vez que uma requisição que necessita de autenticação for realizada, será solicitado as credenciais. Futuramente, sempre que for preciso alterá-las será necessário:

1. Acessar as variáveis de ambiente do insomnia (Atalho `CTRL + E`);
2. Selecionar o ambiente que estão as credenciais;
3. Modificar manualmente o valor `Storage Key` da função `prompt` das variáveis de credenciais desejadas;

> Assim quando a requisição for chamada novamente será solicitado as novas credenciais;

#### 4 - Colaborando com o projeto

A colaboração pode ser realizada normalmente, entretanto, vale destacar que alterações um pouco maiores podem gerar conflitos bem chatos de resolver.
