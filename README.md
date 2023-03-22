# ProjIndMod4-Resilia
Projeto Individual - Módulo 4 - Resilia - Banco de Dados

"A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos."

Esse projeto consiste na criação da modelagem de um banco de dados utilizando um diagrama ER.

# Questões a serem respondidas:

# 1º Existem outras entidades além dessas três?
Resposta: Sim. O número de entidades varia de acordo com o tamanho da empresa/projeto. Além das 3 entidades propostas, adicionei a entidade "Professores", mas da mesma forma poderia ter, por exemplo, uma entidade chamada "Unidades", caso a empresa tivesse mais de uma unidade, tendo talvez até atributos mais especificos, como inscrição municipal, estadual, CNES, etc.

# 2º Quais são os principais campos e tipos?
Resposta: Os principais campos são os utilizados como chave estrangeira, já que são eles os responsáveis pelo relacionamento entre as entidades. Além desses campos, entendo que existem campos principais em todas as entidades, por exemplo:
- Entidade "Empresa": campos Nome e CNPJ;
- Entidade "Cursos": campos Nome e Duração;
- Entidade "Turma": campos Turno, Professor e Alunos;
- Entidade "Professores": campos Nome e Matéria;
- Entidade "Alunos": campos CPF e Turno.

Já os tipos variam de acordo com a informação solicitada, mas os mais utilizados foram: Int, Char e Varchar.

# 3º Como essas entidades estão relacionadas?
Resposta: As entidades estão relacionadas por meio de chaves estrangeiras (FK), sendo estas:

- Cursos_ID;
- Turma_ID;
- Professor_ID;
- Aluno_ID.

Todas conectadas por todos os tipos de cardinalidades, sendo elas:

- 1 – 1 (um para um);
- 1 – N (um para vários) ;
- N – N (vários para vários).

# ___________________________________________________________________

- Martha Lucena - Programadores Cariocas - Resilia Educação.
