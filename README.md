# Projeto ETL Spotify

Este é o projeto ETL com pequenas análises utilizando PySpark no banco de dados do Spotify, realizado durante o Bootcamp de Engenharia de Dados da SoulCode Academy.

## Objetivo
O objetivo deste projeto é extrair os dados da plataforma do Spotify, fazer a limpeza e transformação desses dados e, em seguida, carregá-los em um banco de dados. Além disso, realizamos algumas análises básicas para obter insights sobre as músicas disponíveis no Spotify.

## Tecnologias Utilizadas
- PySpark: para processamento e análise de big data;
- Google Cloud Storage (GCS): para armazenar e acessar os arquivos de dados do Spotify;
- Pandera: para validação de dados e tratamento de inconsistências.

## Resumo do Notebook
O notebook contém as seguintes etapas:

1. Instalações Necessárias: Instalação das bibliotecas necessárias, como PySpark, gcsfs e pandera.

2. Configuração GCS: Configuração da chave de segurança e acesso ao bucket do Google Cloud Storage, onde os dados do Spotify estão armazenados.

3. Configurando SparkSession: Criação da SparkSession com configuração adicional para conexão Spark com o Cloud Storage.

4. Criando DataFrame: Leitura do arquivo CSV que está dentro do bucket do GCS e criação de um DataFrame.

5. Atividade Spark - Spotify: Renomeação das colunas para traduzi-las para o português e pequenas análises das colunas, como ordenação ascendente e descendente.

6. Removendo Duplicatas e Inconsistências: Remoção de linhas duplicadas e tratamento de valores nulos ou inconsistentes em algumas colunas específicas.

7. Conversão e Validação dos Tipos de Dados: Conversão dos tipos de dados para torná-los mais adequados e validação dos dados de acordo com um esquema definido.

8. Análises Interessantes: Apresentação de algumas análises interessantes usando as funções do Spark, como as músicas mais tristes, mais felizes, menos faladas, mais dançáveis, entre outras.

## Conclusões das Análises
Com base nas análises realizadas, obtivemos algumas informações sobre as músicas disponíveis no Spotify. Encontramos músicas com valências de áudio extremas, algumas das mais tristes e outras das mais felizes. Também observamos a quantidade de discurso presente em algumas músicas, que pode indicar faixas que se assemelham a poesias, entrevistas ou audiolivros. Além disso, identificamos músicas com alta danceabilidade, ideais para quem busca animação e energia em suas playlists.

## Contribuições
Este projeto está em constante evolução, e novas análises e melhorias podem ser feitas. Sinta-se à vontade para contribuir, adicionar novas funcionalidades ou realizar análises adicionais nos dados do Spotify. Todas as contribuições são bem-vindas!

## Autor
Este projeto foi desenvolvido por [Giovana de Brito Silva](https://github.com/giobritos), durante o Bootcamp de Engenharia de Dados da SoulCode Academy. Para entrar em contato, você pode enviar um e-mail para giovanadebritos@gmail.com.
