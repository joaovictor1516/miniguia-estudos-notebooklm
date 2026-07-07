# Contexto e Objetivo:
 * ## Usar o NoteboolLM como um professor para os meus estudos no Banco de dados.

# Fontes:
 * ## Fontes de vídeo: 
   * https://www.youtube.com/watch?v=KOhd3R5kLks
   * https://www.youtube.com/watch?v=G7bMwefn8RQ

 * ## Fontes de textos:
   * https://www.ibm.com/br-pt/think/topics/database-normalization
   * https://builtin-com.translate.goog/data-science/advanced-sql?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc
   * https://www.alura.com.br/artigos/normalizacao-banco-de-dados-estrutura?srsltid=AfmBOorMkyNaufIQ0JCNVvLl8UA4bBrpXpJwdjmNbFJ5aE3yGJMtiCe-
   * https://www.datacamp.com/pt/tutorial/normalization-in-sql

# Engenharia de Prompts e "Cicatrizes":
  * ## A principal estrategia de engenharia de prompt que usei foram o uso de instruções claras e a formatação de saída, não foi necesário o refino nos prompts já que a AI está com uma base de dados para a consulta.
  * ## Também utilizei as ferramentas de Ciração de Mapa Mental e de Criação de Slides.

# Miniguia de Estudos:
 * ## Resumo sobre banco de dados:
    * O SQL (Structured Query Language) é a linguagem padrão utilizada para a criação, gerenciamento e manipulação de dados em bancos de dados relacionais. Seu uso abrange desde comandos básicos de consulta até técnicas avançadas de automação e análise de dados.
    Abaixo estão os principais conceitos divididos por categorias fundamentais:
    1. Estrutura e Definição de Dados (DDL)

        Criação de Objetos: O comando CREATE DATABASE inicia um novo banco de dados, enquanto o CREATE TABLE define a estrutura das tabelas, especificando colunas e tipos de dados.
        Tipos de Dados: Os dados podem ser caracteres (char, varchar), numéricos (int, smallint, decimal, money) ou temporais (date, time, datetime).
        Restrições (Constraints): São regras impostas às colunas para garantir a integridade dos dados, como PRIMARY KEY (identificador único), FOREIGN KEY (relacionamento entre tabelas), NOT NULL (valor obrigatório), UNIQUE (valores sem repetição) e CHECK (validação de valores).
        Normalização: Processo de design que organiza os dados para minimizar a redundância e evitar anomalias de inserção, exclusão e atualização. As etapas principais incluem a 1FN (valores atômicos), 2FN (sem dependências parciais) e 3FN (sem dependências transitivas).

    2. Manipulação e Consulta de Dados (DML)

        Comandos Básicos: O SELECT é o comando mais utilizado para recuperar informações. O INSERT adiciona novos registros, o UPDATE altera dados existentes e o DELETE remove linhas específicas.
        Filtragem e Ordenação: A cláusula WHERE aplica filtros baseados em condições lógicas. O ORDER BY classifica os resultados de forma ascendente (ASC) ou descendente (DESC).
        Operadores Especiais:
            DISTINCT: Remove duplicatas do resultado.
            TOP: Limita a quantidade de linhas retornadas.
            BETWEEN, IN e LIKE: Usados para buscar intervalos, listas de valores ou padrões de texto (usando caracteres coringa como %).

    3. Agregação e Junção de Tabelas

        Funções de Agregação: Realizam cálculos em um conjunto de valores para retornar um resumo, como COUNT (contagem), SUM (soma), AVG (média), MIN (mínimo) e MAX (máximo).
        Agrupamento: O GROUP BY divide os resultados em grupos para aplicar funções de agregação, enquanto o HAVING filtra os dados após o agrupamento.
        Junções (Joins): Permitem combinar dados de múltiplas tabelas. O INNER JOIN retorna apenas correspondências exatas. Já os Outer Joins (LEFT, RIGHT, FULL) incluem registros mesmo sem correspondência na outra tabela.

    4. Conceitos Avançados e Programação

        Subconsultas: Uma consulta embutida dentro de outra para alimentar filtros ou colunas.
        Common Table Expressions (CTEs): Conjuntos de resultados temporários nomeados que melhoram a legibilidade do código, podendo ser inclusive recursivas para lidar com dados hierárquicos.
        Views: Tabelas virtuais baseadas em consultas que simplificam o acesso a lógicas complexas.
        Procedimentos Armazenados (Stored Procedures): Lotes de código SQL salvos no banco que podem receber parâmetros e ser executados como uma sub-rotina.
        Triggers (Gatilhos): Códigos disparados automaticamente em resposta a eventos de modificação de dados (INSERT, UPDATE, DELETE).

    5. Otimização e Segurança

        Índices: Estruturas que otimizam a velocidade de recuperação de dados. Podem ser clusterizados (organizam a tabela física) ou não clusterizados (estrutura de busca separada).
        Backup e Restore: Procedimentos essenciais para a proteção contra perda de dados ou corrupção do sistema.

 * ## Mapa mental:
    [Mapa mental](./NotebookLM%20Mind%20Map.png)
 * ## Apresentação criada: 
  [Apresentação sobre sql](./SQL_Engineering_Mastery.pdf)