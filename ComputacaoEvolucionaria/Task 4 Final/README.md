# Projeto Trabalho Final

**Tipo:** Alocação de Recursos.
**Base:** 
* Alocação de professores em suas respectivas cargas horarias
* Em uma semana
* Duas ou mais turmas na semana
* Sem que haja conflito nos horarios.

**Construção da Semana:**
* Semana é uma Matriz com 10 posições (Em uma turma.)
* Cada dia tem 2 posiçoes (1º e 2º Horario, e cada horario são 90 minutos de aula por professor)
* 2 Turmas a Matriz vai ter 20 posições e assim por diante (Para o caso em questão vai ser usado 20 ou 30 posições.
* Cada turma vai ser resolvida por ordem, a 1ª afeta a 2ª e assim por diante (Como se colocasse pontos negativosem determinados dias para alguns professores).


1. Mutação: Troca de posição entre os recursos.
2. Seleção: Até o momento, estou optando por Torneio.
2.1 Cruzamento: 50% Genes do Pai e 50% Genes dam mãe.


[1, 2, 2] = Dia 1, Periodo 2, Professor 2
Não pode ter este mesmo resultado em outras turmas.

Turma 1 = [[1, 2, 0], [2, 2, 0], [4, 3, 1], [0, 3, 1], [2, 2, 2], [1, 2, 2]]
Turma 2 = [[3, 3, 0], [0, 1, 0], [4, 3, 1], [2, 3, 1], [3, 0, 2], [1, 2, 2]]
Turma 3 = [[0, 3, 0], [3, 3, 0], [1, 2, 1], [3, 0, 1], [1, 3, 2], [3, 3, 2]]
Turma 4 = [[4, 0, 0], [1, 1, 0], [4, 3, 1], [3, 0, 1], [4, 2, 2], [2, 0, 2]]