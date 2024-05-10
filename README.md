# projeto_fakenews
Fiz um projeto para o Desafio de Imersão de IA onde fiz um chatbot que detectar se uma notícia é fake news ou não


Este é um chatbot Python simples projetado para combater a desinformação, identificando potenciais notícias falsas.
Funcionalidades:
Verifica se uma notícia contém frases comumente associadas a teorias da conspiração ou informações falsas, 
Pesquisa por notícias relacionadas em fontes confiáveis, incluindo:
Globo
CNN Brasil
BBC News Brasil
Se encontrar notícias relevantes nas fontes confiáveis, informa o usuário que a notícia pode ser falsa e fornece links para as fontes confiáveis para verificação.
Se não encontrar informações relevantes nas fontes confiáveis, informa ao usuário que não há evidências suficientes para confirmar ou negar a veracidade da notícia.
Como usar:
Instalação:
Certifique-se de ter o Python 3 instalado em seu sistema.
Instale a biblioteca requests: pip install requests
Execução:
Execute o script Python chatbot.py (renomeie o arquivo do código para chatbot.py).
O chatbot solicitará que você insira uma notícia.
Após inserir a notícia, o chatbot fornecerá um resultado, indicando se encontrou evidências de que a notícia pode ser falsa ou não.
Exemplo:
Entrada: Céu ficou verde por todo mundo afirmando que a Terra é Plana
Saída: Em nenhum momento a Terra teve o céu verde e isso não afirma que a terra é plana, já que não há evidências que os terraplanistas deram isso como evidência. Veja abaixo notícias sobre o formato da terra ou sobre o que acontece na atmosfera do Planeta:
Link da notícia Globo
Link da notícia CNN Brasil
Link da notícia BBC Brasil
