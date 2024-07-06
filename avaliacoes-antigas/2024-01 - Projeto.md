O objetivo do segundo trabalho é que vocês façam uma análise exploratória nos dados referentes às músicas mais streamadas no Spotify no ano de 2023. O arquivo está disponível para download em [aqui](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/). O arquivo a ser baixado é um `.zip` contendo o arquivo `spotify-2023.csv`, que deverá ser carregado no `R` para ser feita a análise exploratória.


* ATENÇÃO: O arquivo tem uma linha problemática, a linha 576, referente à música "Love Grows (Where My Rosemary Goes)", de Edison Lighthouse. Sugiro removê-la (antes ou depois de carregar no `R`, tanto faz), para não "contaminar" a análise. Verifique se há outras linhas problemáticas.


Este conjunto de dados contém uma lista abrangente das músicas mais populares de 2023, conforme listado no Spotify. O conjunto de dados oferece uma riqueza de características além do que é tipicamente disponível em conjuntos de dados similares. Ele fornece diversos atributos de cada música, popularidade e presença em várias plataformas de música. O conjunto de dados inclui informações como nome da faixa, nome(s) do(s) artista(s), data de lançamento, playlists e rankings do Spotify, estatísticas de streaming, presença no Apple Music, presença no Deezer, rankings do Shazam e várias características de áudio. Segue abaixo uma descrição das colunas da base de dados:

* track_name: Nome da música
* artist(s)_name: Nome do(s) artista(s) da música
* artist_count: Número de artistas que contribuíram para a música
* released_year: Ano em que a música foi lançada
* released_month: Mês em que a música foi lançada
* released_day: Dia do mês em que a música foi lançada
* in_spotify_playlists: Número de playlists do Spotify em que a música está incluída
* in_spotify_charts: Presença e posição da música nos rankings do Spotify
* streams: Número total de streams no Spotify
* in_apple_playlists: Número de playlists do Apple Music em que a música está incluída
* in_apple_charts: Presença e posição da música nos rankings do Apple Music
* in_deezer_playlists: Número de playlists do Deezer em que a música está incluída
* in_deezer_charts: Presença e posição da música nos rankings do Deezer
* in_shazam_charts: Presença e posição da música nos rankings do Shazam
* bpm: Batidas por minuto (uma medida da "velocidade" da música)
* key: Tom da música (essa é uma informação bastante musical, e essencialmente significa em torno de qual "nota" a música está "orbitando". Se você não está familiar com teoria musical, pode ignorar esse atributo.)
* mode: Modo da música (maior ou menor) (essa também é uma informação bastante musical, e essencialmente significa a "forma" como acontece a "nota" em torno do qual a música está "orbitando". Se você não está familiar com teoria musical, pode ignorar esse atributo também.)
* danceability_%: Porcentagem indicando quão adequada a música é para dançar
* valence_%: Positividade do conteúdo musical da música
* energy_%: Nível percebido de energia da música
* acousticness_%: Quantidade de som acústico na música
* instrumentalness_%: Quantidade de conteúdo instrumental na música
* liveness_%: Presença de elementos de performance ao vivo
* speechiness_%: Quantidade de palavras faladas na música

Você deverá escrever um relatório reportando sua análise exploratória no formato indicado no arquivo `MODELO DE RELATÓRIO DE AED`, em anexo na atividade no Google CLassroom. Adicionalmente, o relatório deverá conter um apêndice com os comandos em `R` que você utilizou em sua análise e para gerar as informações nele expostas. O seu relatório deverá conter discussões sobre:
* O propósito da base de dados, ou seja, o que se pode fazer com a informação contida na base.
* Como as variáveis se relacionam entre si (por exemplo, estudo da correlação entre as variáveis quantitativas, dentre outros)
* Comportamento individual, estatísticas sumário e descrição das variáveis.
* Existência e comportamento de dados faltantes.
* Qualquer outra coisa que você julgar necessário e importante.
Seu trabalho pode (e deve!) conter figuras e/ou tabelas informativas sobre a base de dados. Cada figura/tabela deve ser devidamente explicada no texto, e alguma conclusão dela deve ser extraída. O seu texto deve estar organizado, conciso e informativo. Textos fora da formatação indicada acima terão a nota penalizada.
