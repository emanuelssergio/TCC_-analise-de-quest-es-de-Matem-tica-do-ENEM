# 📊 TCC - Análise de Questões de Matemática do ENEM

Este repositório contém os códigos, scripts e análises desenvolvidos como parte do Trabalho de Conclusão de Curso (TCC) em Engenharia da Computação. O projeto tem como foco a análise aprofundada das questões de Matemática do Exame Nacional do Ensino Médio (ENEM), explorando padrões, níveis de dificuldade e o desempenho dos candidatos com base nos microdados oficiais.

## ⚠️ Importante: Obtenção dos Dados

Devido ao grande volume de informações e aos limites de armazenamento do GitHub, **alguns arquivos de dados brutos não estão incluídos neste repositório**. 

Para executar as análises localmente e reproduzir os resultados, é necessário baixar os **Microdados do ENEM** diretamente do portal oficial do INEP. 

**Como obter os dados faltantes:**
1. Acesse o portal do INEP: [Microdados do ENEM](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem)
2. Faça o download dos arquivos referentes aos anos analisados neste projeto.
3. Extraia os arquivos e coloque as bases de dados (geralmente arquivos `.csv` ou `.txt` grandes) na pasta `dados/brutos/` (ou no diretório especificado na configuração do projeto).
4. Após isso, os scripts de limpeza e processamento poderão ser executados normalmente.

## 🛠️ Tecnologias Utilizadas

O desenvolvimento das análises e o processamento dos dados foram realizados utilizando o ecossistema de dados da linguagem Python:

* **Python 3.x**
* **Pandas:** Para manipulação, limpeza e estruturação dos datasets.
* **Scikit-learn / TensorFlow:** Para eventuais modelagens e análises estatísticas mais avançadas.
* **Matplotlib / Seaborn:** Para a visualização de dados e geração de gráficos.
* **Jupyter Notebook:** Para documentação e execução interativa das análises exploratórias.

🚀 Como Executar o Projeto

Este projeto foi feito usando a plataforma do Google colab, mas se deseje usar o arquivo local e so seguir o passo a passo a seguir


Clone o repositório:
git clone https://github.com/emanuelssergio/TCC_-analise-de-quest-es-de-Matem-tica-do-ENEM.git

Acesse a pasta do projeto:
cd TCC_-analise-de-quest-es-de-Matem-tica-do-ENEM

Crie um ambiente virtual e instale as dependências:
python -m venv venv
source venv/bin/activate (No Windows use: venv\Scripts\activate)
pip install -r requirements.txt

Adicione os Microdados:
Baixe os microdados conforme explicado na seção "Obtenção dos Dados" e mova-os para a pasta correspondente.

Execute os Notebooks ou Scripts:
Inicie o Jupyter e abra os arquivos da pasta notebooks/ para visualizar o passo a passo da análise.


✒️ Autor
Emanuel Silva Sergio
Engenharia da Computação
