# Solução de Pesquisa Cognitiva do Azure (Azure Cognitive Search)

##  Utilizando AI Search para indexação e consulta de Dados

Vamos criar nosso Storage e permitir acesso anônimo ao blob.
![imagem1](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img01.png)


![imagem2](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img02.png)

Vamos criar um novo  Container
![imagem3](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img03.png)


![imagem4](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img04.png)

Vamos acessar o container 'cofferviews' recém criado para adicionar arquivos.
![imagem5](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img05.png)

Clicando em 'Carregar', selecionaremos os arquivos baixados da documentão do Azure
![imagem6](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img06.png)


![imagem7](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img07.png)


![imagem8](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img08.png)


![imagem9](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img09.png)

Após carregar os documentos, voltaremos no início e acessaremos nosso serviço de pesquisa.
![imagem10](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img10.png)

Importaremos os documentos clicando em 'Importar dados'.
![imagem11](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img11.png)

Na tela 'Importar dados', vamos inserir o nome da fonte de dados igual ao container criado e escolheremos um conexão existente.
![imagem12](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img12.png)


![imagem13](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img13.png)

Vamos avançar até criar.
![imagem14](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img14.png)


![imagem15](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img15.png)

Vamos clicar em 'Gerenciador de pesquisa' após estar pronto.
![imagem16](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img16.png)


![imagem17](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img17.png)

No Gerenciador de pesquisa podemos realizar pesquisas. 
Podemos verificar se a indexação está funcionando e mostrar os documentos através do código:
``` search=*$&$count=true```
![imagem18](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img18.png)

No exemplo abaixo, será pesquisado as ocorrências em Chicago, através do código:
```search=locations:'Chicago'```
![imagem19](https://github.com/franciscampos91/microsoft-azure-ai-fundamentals-dio/blob/main/DP05%20-%20Azure%20Cognitive%20Search/prints/img19.png)

## Considerações finais

  
O Azure Cognitive Search é um serviço de pesquisa permite aos desenvolvedores adicionar capacidades de pesquisa avançadas aos seus aplicativos e sites. Ele oferece recursos poderosos de pesquisa baseados em inteligência artificial e aprendizado de máquina para ajudar na descoberta de insights e informações relevantes em grandes volumes de dados. Desta forma, é possível realizar buscas em documentos digitalizados, em formato de imagem ou PDF, para buscar palavras chaves ou sentimentos.
