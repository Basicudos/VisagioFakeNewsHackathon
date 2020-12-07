# VisagioFakeNewsHackathon
## Ferramenta desenvolvida para detectar fake news e identificar através de tweets relacionados à notícia se a desinformação foi propagada ou não.
A proposta elaborada pelo grupo *Basicudos* consiste em primeiramente detectar caso a notícia seja fake news através das manchetes. Caso haja alguma notícia falsa detectada, a avaliação sentimental é feita nos tweets que se referem à notícia, para detectar se a desinformação foi passada à frente ou se foi detectada pela população.
A classificação da Fake News foi feita a partir das respostas das 10 questões disponíveis no banco de dados. Para cada notícia, se há mais respostas 'Satisfatórias' às perguntas, então esta notícia é considerada verdadeira. Caso contrário é *fake news*.
Diversos modelos foram avaliados e testados. O processo inteiro se encontra em Pipeline_Final.ipynb.
