# Análise de Sentimentos aplicado à discursos políticos
 Como podemos avaliar os discursos políticos em relação ao tom do discurso, em positivo, negativo ou neutro? Ao longo do tempo o tom do discurso muda? Se tivessemos mais dados poderiamos correlacionar com acontecimentos históricos ou situações específicas no país, são hipóteses que poderiam ser respondidas.
 
 Este projeto está dividivo em 3 partes e analisaremos somente em relação aos textos transcritos dos discursos do atual presidente, coletados em fontes oficiais públicas.
 
 ## Parte 1: coleta de dados
 A coleta de dados foi realizada por meio de web scraping por meio principalmente do *chromedriver* e uso da biblioteca *beautifulsoup*.
 
 ## Parte 2: limpeza de dados
 Nesta parte encontramos os padrões e removemos as **tags** e **classes** do código fonte HTML das páginas, mantendo os textos de nosso interesse.
 
 ## Parte 3 e 4: Modelagem de tópicos e análises de sentimentos
 Identificamos as palavras mais importantes de cada tópico e pra isso foram utilizadas *SpaCY*, *CountVectorizer*, *tf-idf*, *NMF* do *Scikit-Learn*.
 Para as análises de sentimentos foi utilizado um léxico de sentimentos, o **SentiLex-PT 02** e por fim fizemos uma análise ao longo do tempo com as amostras coletas.
