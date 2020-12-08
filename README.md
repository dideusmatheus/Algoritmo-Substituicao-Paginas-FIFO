# Implementação da politica de substituição de Paginas FIFO
## Alunos: Francisco Carlos Ramos Ferreira Filho 4889, Gabriel Guimarães Batalha 3915 e Matheus de Deus Rocha  3918.
### Neste repositorio se incontra a implementação da politica de substituição
* Gerenciador de memoria
* Algoritmo de Substituição FIFO
* Algoritmo de Substituição RANDOM
#### BUGSS - ALGORITMO FIFO SEMPRE RETORNA A MESMA QUANTIDADE DE PÁGINAS
##### Como compilar o Algoritmo 
* gcc -Wall main.c -o vmm 
* ./vmm FIFO 10 < anomaly.dat OU ./vmm RANDOM 10 < anomaly.dat