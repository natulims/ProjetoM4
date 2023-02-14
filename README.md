<h1 align="center">Projeto Individual - Módulo 4 👩‍💻</h1>

<h3>Proposta</h3>
<div style="display: inline_block"><br>
Criar um novo sistema de acompanhamento e pra isso foi necessário modelar um banco de dados que irá armazenar os cursos, turmas e alunos.</div>

<h2>Perguntas e Respostas relacionadas ao Projeto</h2>
Existem outras entidades além dessas três?
<p>R: Sim! Deve ser levado em consideração o instrutor, o qual é responsável pelo aprendizado dos alunos e suas matriculas.
<br></p><hr>
<p>Quais são os principais campos e tipos?

R: ID - Utiliza o campo INTEGER 

Nome - Utiliza o campo VARCHAR

CPF - Utiliza o campo VARCHAR

Email - Utiliza o campo VARCHAR

Valor_Hora - Utiliza o campo INTEGER

Carga_Hr - Utiliza o campo SMALLINT

Data - Utiliza o campo DATE

Preço - UTILIZA o campo DOUBLE ou DOUBLE PRECISION
<br>
</p><hr>
<p>Como essas entidades estão relacionadas?

R: Primeiramente foi feita a entidade curso para ser usada de base, através dela foi inserido nome, carga horária, requisito e preço. O requisito é o que o aluno necessita para fazer o curso. A carga horária é o tempo necessário para cumprir com o curso e, por último, o valor do curso. Após terem sido criadas, foi adicionada as entidades instrutor, matriculas, alunos e turmas! Existe uma relação entre turmas e matriculas, sendo assim, só será possível ter novas matriculas caso haja turmas disponíveis. E através dessa entidade há uma relação entre alunos e matriculas, portanto, é necessário que exista matriculas suficientes para todos os alunos.
Por fim, as entidades turmas e cursos foram utilizadas da carga horária, onde cada curso tem uma carga horária que pode variar de curso pra curso.</p>
