## *Respostas das perguntas*
1. Existem outras entidades além dessas três?

R: Dentro dessas três entidades (aluno, curso e turmo) no diagrama foi levado em consideração o instrutor no qual é responsavel no aprendizado dos alunos e as matriculas

2. Quais são os principais campos e tipos?

ID - Utiliza o campo INTEGER 

Nome - Utiliza o campo VARCHAR

CPF - Utiliza o campo VARCHAR

Email - Utiliza o campo VARCHAR

Valor_Hora - Utiliza o campo INTEGER

Carga_Hr - Utiliza o campo SMALLINT

Data - Utiliza o campo DATE

Preço - UTILIZA o campo DOUBLE ou DOUBLE PRECISION

3. Como essas entidades estão relacionadas?

Primeiro foi feito a entidade curso como base para o diagrama e nela possui Nome, carga horaria, requisito e preço. Requisito é o que o aluno necessita para poder fazer aquele curso, a carga horária o tempo do curso e por ultimo o valor do curso.
Depois de ter feito o curso foi criada as entidades instrutores, matriculas, alunos e turmas, e existe uma relação entre turmas e matriculas, sendo assim, só podendo haver vagas para novas matriculas se tiver turmas disponiveis, e dentro dessa entidade tem uma relação com alunos porque para se ter uma matricula e necessario ter alunos.
E por ultimo nas entidades turmas e cursos utilizei o campo em comum carga_Hr, porque a carga horaria de um curso pode variar e isso pode prejudicar os dados ao se fazer um relatorio.
