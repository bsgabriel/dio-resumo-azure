# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

Esse LAB foi feito seguindo a seguinte documentação: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

## Criação de Serviços

### Serviço de Pesquisa
Primeiro, foi criado um serviço de pesquisa:
![Criação de Serviço de Pesquisa](images/1-criacao_servico_pesquisa.png)

### Serviço de IA
Depois foi criado um serviço de IA:
![Criação de Serviço de IA](images/2-criacao_servico_ai.png)

### Serviço de Armazenamento
Por fim, foi criado um serviço de armazenamento:
![Criação de Serviço de Armazenamento](images/3-criacao_storage.png)

Habilitei o acesso anônimo aos arquivos:
![Configuração Acesso Anônimo](images/3_1-habilitar_acesso_anonimo.png)

Para poder armazenar os documentos, criei um contêiner:
![Criação de Contêiner de Armazenamento](images/4-criacao_container_armazenamento.png)

Após a criação do contêiner, realizei o upload dos arquivos (fornecidos na documentação):
![Upload de Arquivos](images/5-arquivos_adicionados.png)

## Importação de Dados
Através de uma série de configurações (das quais acabei não tirando muitos prints), realizei a importação dos dados adicionados anteriormente. Agora, posso usar eles no serviço de pesquisa

## Exeplo de Buscas

### Pesquisa por Localização
Fiz uma breve pesquisa por Chicago, tendo vários resultados:
![Pesquisa por Localização Chicago](images/7-busca1-chicago.png)

### Pesquisa por Sentimentos
Pesquisei também por sentimentos positivos (aquilo que a IA entende como sendo algo bom). Foram 5 resultados:
![Pesquisa por Sentimento Positivo](images/7-busca2-sentimento_positivo.png)

Resolvi pesquisar por sentimentos negativos, para ver se tinha algo de ruim. Tive apenas um resultado:
![Pesquisa por Sentimento Negativo](images/7-busca3-sentimento_negativo.png)