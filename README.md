# MVP-Analise-de-Dados-e-Boas-Praticas

Pontifícia Universidade Católica do Rio de Janeiro / Pós-Graduação em Ciência de Dados e Analytics / Disciplina: Sprint -  Análise de Dados e Boas Práticas (40530010055_20260_01)


### *MVP - (Minimum Viable Product)*
## Internações Hospitalares no Setor Privado Suplementar de Saúde no Estado de São Paulo em dezembro de 2024  

### Objetivo
Este projeto apresenta a Análise de Dados Exploratória (EDA) de conjunto de dados de Internações Hospitalares no Setor Privado Suplementar de Saúde no Estado de São Paulo em dezembro de 2024. Tem como objetivo analisar dados de tempo de permanência dos pacientes na internação hospitalar, a partir de caracteríticas como faixa etária, sexo dos pacientes e tipo de doença ou condição de saúde, considerando o código CID (Classificação Internacional de Doenças). 

### Conjunto de dados (SP_202412_HOSP_CONS.csv)

O conjunto de dados é disponibilizado pela Agência Nacional de Saúde Suplementar – ANS no Portal de Dados Abertos - PDA (https://www.gov.br/ans/pt-br/acesso-a-informacao/perfil-do-setor/dados-abertos-1).

Foi selecionada a competência mais recente disponível (dezembro de 2024) e a Unidade da Federação com maior quantidade de internações hospitalares (São Paulo) (https://dadosabertos.ans.gov.br/FTP/PDA/TISS/HOSPITALAR/2024/SP/SP_202412_HOSP_CONS.zip).

O conjunto de dados foi selecionado para o presente trabalho por possuir diferentes características, possibilitando que sejam exploradas diferentes condições, que podem ou não estar associadas ao tempo de permanância na internação hospitalar.

Considerando que o Portal de Dados Abertos observa parâmetros legais da Lei Geral de Proteção de Dados, não há restrições relativas à disponibilização do conjunto de dados e de suas análises decorrentes.


### Notebook do Google Colab, composto por: 
- Descrição do Problema
- Hipóteses do Problema
- Tipo do Problema
- Seleção de Dados
- Atributos do Dataset
- Importação das bibliotecas necessárias e carga de dados
- Análise de Dados Exploratória - EDA
- Considerações sobre pré-processamento de dados
- Respondendo às hipóteses
- Conclusão


### Síntese
Este estudo demonstrou a importância de fatores como a faixa etária e o tipo de doença na determinação do tempo de internação hospitalar. Assim, a análise dessas características no conjunto de pacientes e de internações hospitalares pode subsidiar estratégias das operadoras de planos de saúde e hospitais no planejamento e na gestão de recursos, contribuindo para a qualidade e sustentatibilidade da atenção à saúde. A preponderância de internações de curta duração (1 dia) e a existência de internações de longa duração destacam a necessidade de considerar as características relacionadas ao tempo de permanência dos pacientes nas internações hospitalares.


### Como Executar
Acesse o notebook no Google Colab

Execute todas as células em ordem: Runtime → Executar todas

Nenhuma instalação adicional é necessária — todas as bibliotecas utilizadas estão disponíveis por padrão no Colab
