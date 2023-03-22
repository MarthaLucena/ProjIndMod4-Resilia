# ProjIndMod4-Resilia
Projeto Individual - Módulo 4 - Resilia - Banco de Dados

"A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos."

# Esse projeto consiste na criação da modelagem de um banco de dados utilizando um diagrama ER.

# Questões a serem respondidas:

# 1º Existem outras entidades além dessas três?
Resposta: Sim. O número de entidades varia de acordo com o tamanho da empresa/projeto. Além das 3 entidades propostas, adicionei a entidade "Professores", mas da mesma forma poderia ter, por exemplo, uma entidade chamada "Unidades", caso a empresa tivesse mais de uma unidade, tendo talvez até atributos mais especificos, como inscrição municipal, estadual, CNES, etc.

# 2º Quais são os principais campos e tipos?
Resposta: Os principais tipos utilizados foram: 1-1 (um para um) e 1-N (um para muitos). Já os principais campos utilizados foram ID, Nome e CPF, já que todos estes, cada qual em sua respectiva entidade, foram utilizados como chaves primárias e chaves estrangeiras.

# 3º Como essas entidades estão relacionadas?
Resposta: As entidades estão relacionadas por meio de chaves estrangeiras (FK), sendo estas:

- Cursos_ID;
- Turma_ID;
- Professor_ID;
- Aluno_ID.
