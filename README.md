Exercício Prático: Modelagem de Dados EVG (Escola Virtual de Governo)
Este repositório contém a resolução do Exercício Prático II do módulo de Business Intelligence II. O objetivo foi transformar uma tabela desnormalizada (One Big Table) em um modelo dimensional Star Schema utilizando o Power BI e o formato de projeto .pbip.

🎯 Objetivo
Aplicar conceitos de modelagem de dados avançada, incluindo a criação de chaves substitutas (surrogate keys), separação de tabelas Fato e Dimensão, e documentação de modelos conceituais e lógicos.

📊 Visualização do Dashboard
(Nota: Certifique-se de que o nome do arquivo da imagem no GitHub seja exatamente "modelo desenhado.jpeg")

🛠️ Etapas Realizadas
Versionamento: Configuração de repositório Git com .gitignore para ignorar arquivos pesados (.csv, .abf).

Modelagem Dimensional:

Tabela Fato: Fato_Matriculas (contendo chaves e métricas de eventos).

Tabelas Dimensão: Dim_Alunos, Dim_Cursos, Dim_Turmas, Dim_Status.

Tratamento de Dados (Power Query):

Criação de chaves substitutas.

Remoção de chaves naturais da tabela fato para otimização.

Ajuste de tipos de dados.

Relacionamentos: Implementação de esquema estrela (Star Schema) com cardinalidade 1:N e direção de filtro única (Dimensão -> Fato).

💡 Perguntas de Negócio Respondidas
Com base no dashboard desenvolvido, buscamos responder:

Qual o total de alunos e matrículas realizadas?

Qual a distribuição de alunos por status de conclusão (Concluída, Desistente, Reprovado)?

Qual o desempenho médio por curso oferecido pela EVG?

📁 Estrutura do Repositório
/data: (Pasta ignorada pelo Git conforme instruções do exercício).

sophia_bi2.pbip: Arquivo de projeto do Power BI.

.gitignore: Filtro de arquivos para segurança e performance do repositório.

Desenvolvido por: Sophia silva melo
Curso: Business Intelligence II - Exercício Prático II
