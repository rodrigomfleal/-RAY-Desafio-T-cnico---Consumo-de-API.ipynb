# Ray - Desafio Técnico: Consumo de API

## Como Rodar o Projeto:

### Pré-requisitos:

Antes de executar o código, você precisa de uma chave de API do YouTube. 
Para obter uma chave, siga as instruções abaixo:

- Acesse o Google Cloud Console.
- Crie um projeto.
- Habilite a YouTube Data API v3 na Biblioteca.
- Gere uma chave de API.


### Passos para executar

1. Instalar as dependências:

- Necessa biblioteca google-api-python-client. Para instalá-la, execute o seguinte comando:
bash
Copy code
pip install --upgrade google-api-python-client
Obter a chave de API:

Substitua a variável api_key no código pela chave de API que você gerou.
Rodar o código:

Após inserir a chave de API, basta rodar o script Python. Ele irá acessar a playlist de vídeos de highlights da Fórmula 1, buscar as informações dos vídeos e gerar o ranking de acordo com as visualizações.
Exemplo de execução:
bash
Copy code
python ranking_f1_videos.py
Após a execução, o script exibirá o ranking dos vídeos mais assistidos, com base nas visualizações.
