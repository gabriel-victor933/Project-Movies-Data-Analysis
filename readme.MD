# 🎬 Análise de Dados do Cinema IMDB

# 📌 Sobre o Projeto
Este projeto explora a evolução da indústria cinematográfica desde a sua origem, utilizando dados públicos do IMDB. A análise abrange tendências de produção ao longo das décadas, duração média dos filmes, gêneros mais populares e uma lista dos filmes mais bem avaliados de todos os tempos, com base em um sistema de normalização do número de avaliações.

O objetivo principal foi identificar padrões históricos e insights relevantes sobre a trajetória do cinema mundial, utilizando análise de dados como ferramenta de exploração.

# 🗂️ Fontes de Dados
IMDB - Non-Commercial Datasets
História do Cinema - Academia Internacional de Cinema

# ⚙️ Tecnologias Utilizadas
Linguagem: Python 3.10
Bibliotecas:
Pandas (manipulação e limpeza de dados)
Matplotlib (criação de gráficos e visualizações)
# 🔎 Etapas do Projeto
Coleta de Dados
Importação dos datasets do IMDB e fontes externas sobre a história do cinema.

Limpeza e Preparação dos Dados

Tratamento de valores nulos
Conversão de tipos de dados
Normalização dos dados para análise mais robusta
Análise Exploratória de Dados (EDA)

Evolução do número de filmes produzidos ao longo das décadas
Análise de tendências de gênero
Estudo sobre a duração dos filmes
Identificação dos filmes com melhores avaliações ponderadas
Visualizações
Gráficos de linha, área e dispersão para ilustrar tendências e insights relevantes.

# 📊 Principais Insights
🔹 Evolução da Produção de Filmes

Desde 1895, a quantidade de filmes produzidos vem aumentando continuamente.
A grande explosão do cinema ocorreu na década de 1910.
Houve um leve declínio na produção durante a década de 1940, possivelmente influenciado pela Segunda Guerra Mundial.
Entre 1950 e 1990, houve uma redução no ritmo de crescimento, seguida de uma retomada no período recente.

🔹 Duração dos Filmes

A duração média dos filmes aumentou até atingir um platô por volta de 1960, mantendo-se próximo de 1 hora e 40 minutos.
Existe uma alta variabilidade na duração, com filmes curtos e longas-metragens convivendo em diferentes épocas.
🔹 Gêneros de Filmes

O drama sempre foi o gênero mais produzido desde o início da história do cinema.
Observa-se uma tendência de queda na porcentagem de filmes de drama nos últimos anos.
Os documentários ganharam relevância após 1990, crescendo significativamente em participação.

🔹 Top 10 Filmes Mais Bem Avaliados (com normalização para considerar número de avaliações):

## 🎥 Top 10 Filmes Mais Bem Avaliados (Nota Normalizada)

| Rank | Filme                                                        | Nota Normalizada |
|------|--------------------------------------------------------------|------------------|
| 1    | The Shawshank Redemption                                     | 9.30             |
| 2    | The Godfather                                                | 9.20             |
| 3    | The Chaos Class                                              | 9.13             |
| 4    | Attack on Titan the Movie: The Last Attack                   | 9.04             |
| 5    | Ramayana: The Legend of Prince Rama                          | 9.02             |
| 6    | The Dark Knight                                              | 9.00             |
| 7    | The Lord of the Rings: The Return of the King                | 8.99             |
| 8    | Schindler's List                                             | 8.99             |
| 9    | The Godfather Part II                                        | 8.99             |
| 10   | 12 Angry Men                                                 | 8.99             |

# ✅ Conclusões
A indústria cinematográfica tem se expandido de forma consistente desde o final do século XIX, com picos e quedas explicáveis por fatores históricos e tecnológicos.
A preferência por gêneros tem mudado, refletindo as demandas do público e inovações no cinema.
A análise normalizada de ratings permite uma avaliação justa e equilibrada dos filmes mais bem avaliados, considerando a quantidade de votos recebidos.
# 📁 Como Executar o Projeto
Clone o repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git
Acesse o diretório do projeto:
cd nome-do-projeto
Instale as dependências:
pip install -r requirements.txt
Execute o notebook ou script principal:
python analise_imdb.py

# 🚀 Diferenciais do Projeto
Análise histórica e temporal de mais de um século de dados.
Normalização de ratings ponderados pelo número de avaliações, garantindo maior robustez nas conclusões.
Visualizações intuitivas e de fácil interpretação, mesmo para quem não é da área técnica.