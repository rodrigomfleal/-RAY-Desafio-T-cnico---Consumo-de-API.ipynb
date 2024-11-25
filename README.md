# Ray - Desafio Técnico: Consumo de API

## Como Rodar o Projeto:

### Passos para executar

1. Acesse o Google Colab:

- Abra o navegador e acesse Google Colab;
- Faça login com sua conta do Google, se necessário;

2. Crie um Novo Notebook:

- Clique em "File" (Arquivo) no menu superior e selecione "New Notebook" (Novo notebook).

3. Insira o Código:

- Copie o código que você criou e cole na célula inicial do notebook.
- Se o código estiver dividido em partes (múltiplas células), insira cada parte em células separadas.

4. Caso necessário, substitua a Chave da API:

No código, localize a variável "api_key" e substitua o valor detro das aspas para a sua chave api.

- Para gerar a chave api, basta:

a) Acesse o Google Cloud Console https://console.cloud.google.com/welcome.

b) Crie um projeto;

c) Habilite a Youtube Data API v3 na Biblioteca da parte de API e Serviços;

d) Gere uma chave de API;

5. Execute as Células do Código:

- Caso tenha uma célula só, para rodar o código, clique no botão de play ao lado da célula;
- Caso tenha colocado em mais de uma célula, no menu superior em "Ambiente de Execução" e opte pela opção "Executar Tudo";


## Decisões Técnicas:

1. Utilizei a documentação da API do Youtube para verificar os métodos corretos a serem utilizados para me auxiliar, como o playlistItems e videos, para conseguir extrair o necessário;
2. Usei a biblioteca Pandas para organizar os dados e fazer a exibição da lista solicitada dos vídeos ordenados por número de visualizações, devido a minha familiaridade com a biblioteca e já ter um certo conhecimento utilizando-a;
3. Em determinado momento do código, utilizei a função "extend()" para adicionar as informações estatísticas dos vídeos em uma lista em vez de usar o "append()", isso se deu por causa da maneira diferente que os métodos adicionam os itens na lista;

## Desafios Encontrados:

1. O principal desafio foi utilizar uma biblioteca com a qual eu não tinha experiência prática, foi desafiador entender quais parâmetros passar corretamente e como ter o resultado esperado, mas pesquisando consegui entender um pouco melhor o funcionamento e realizar o pedido;
2. Além da API ter sido desafiadora em sí, em alguns momentos tive dificuldades em encontrar os parâmetros corretos para utilizar nas consultas, principalmente ao tentar buscar as estatísticas dos vídeos, que eram por outro método da API;
3. Normalmente, eu utilizo "append()" para adicionar elementos a listas, mas na parte do código em que busquei as estatísticas dos vídeos, precisei usar "extend()". Inicialmente, tive dificuldades em entender a diferença entre ambos os métodos e qual seria o mais adequado para esse caso,  porém fazendo pesquisas consegui enxergar que o uso do "extend()" seria o mais adequado para a situação;
