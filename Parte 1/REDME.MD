Anotações:

Estudo de caso 1:

Você tem um determinado cliente que é uma loja on line e ela vende vários produtos.
E quando é feito um novo pedido o cliente vai lá no site faz um pedido você precisa fazer a separação automática dos produtos que o cliente pediu. 

1. Definição do ambiente
 - Definição dos Estados ------------------- Definição do estado atual do robo em números ex. localização A = 0, B =1, C = 2 etc...

 - Definição das Ações --------------------- Definição das possíveis ações do robo ex. o estado 0 só pode ir para o estado 1, o estabo 1 pode ir para o 0 ou 2 ou 3 etc...
                                             S(estado) = {0,1,2,3,4,5,6,7,8,9,10,11}
                                             A(ação) = {0,1,2,3,4,5,6,7,8,9,10,11}

 - Definição das Recompensas --------------- Definição das recompesas até chegar ao local que o robo terá a reconpensa maior ex: S   0|1|2|3|4|5|6|7|8|9|10|11
                                                                                                                                   0|0,1,0,0,0,0,0,0,0,0, 0, 0
                                                                                                                                   1|1,0,1,0,0,1,0,0,0,0, 0, 0
                                             OBS: A reconpensa para o valor de destino deve ser maior que o comum (1)!
                        

2. Solução de IA (Intuição Teórica)
 - Markov Decision Processes
 - Q-Learning

3. Implementação em IA
 - Construção da Solução de IA
 - Entrando em Produção
 - Melhorias da Solução de IA

4. Descrição das apredizagens
 - O que é aprendizagem por reforço -------- Aprendizagem por Reforço = O robo (agente) aprende conforme suas recompensas, nesse processo o agente aprenderá explorando ambiente.
                                             Aprendizagem Supervisionada = Apredizagem que exige um Banco de Dados, onde o algoritmo processa e retorna o valor.
 - A equação de Bellman
 - O "Plano"
 - Markov Decision Processes (MDP)
 - Política x Plano
 - Adição de penalidade
 - Q-Learning - Intuição
 - Diferença Temporal
 - Q-Learning - Visualização