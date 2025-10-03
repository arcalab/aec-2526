
<br>

# Introdução e objectivos

Esta unidade curricular visa tornar os estudantes aptos a analisar algoritmos
do ponto de vista da sua correcção e tempo de execução. Visa também tornar os
estudantes proficientes na utilização de estruturas de dados avançadas, por
exemplo grafos. A UC introduz ainda conceitos elementares de complexidade
algorítmica, tais como a noção do problema NP-completo.

1. Introdução à análise de correção de algoritmos: pré e pós-condições;
   invariantes de ciclo; anotação de programas.
2. Análise de tempo de execução de algoritmos: modelo de complexidade
   assimptótica; estratégias algorítmicas; recorrências; análise de melhor
caso, pior caso, e caso médio; análise amortizada; casos de estudo.
3. Estruturas de dados eficientes: árvores AVL, tabelas de dispersão, heaps.
   Implementação eficiente de buffers e dicionários.
4. Algoritmos fundamentais sobre grafos; estratégia algorítmica greedy e
   programação dinâmica.
5. Introdução às classes de problemas de decisão P, NP, e NP-completo.



<br>
# Programa // Plano 

| Datas            | TPs                                   | Ts                                                                 |
|------------------|---------------------------------------|--------------------------------------------------------------------|
| 15.Set a 19.Set  |                                       | Apresentação. Introdução à correcção de Programas Imperativos. Especificações e triplos de Hoare |
| 22.Set a 25.Set  | [Ficha 1.1 (Especificações)](./ficha1tp.pdf)            | Validade de um Triplo de Hoare. Regras de prova: Sequencia, atribuição e condicionais |
| 29.Set a 3.Out   | Ficha 1.2 (Correcção)                 | Correcção de ciclos: variantes e invariantes.                      |
| 6.Out a 10.Out   | Ficha 1.3 (Invariantes)               | Introdução à análise de complexidade. Tamanho do input. Melhor e pior casos. Caso médio. |
| 13.Out a 17.Out  | Ficha 2.1 (Contagem)                  | Análise de definições recursivas. Relações de recorrência. Complexidade de algoritmos de ordenação. |
| 20.Out a 24.Out  | Ficha 2.2 (Recorrências)              | Análise amortizada                                                 |
| 27.Out a 30.Out  | Ficha 2.(3,4) (Caso médio/Amortizada) | Estruturas de dados para representar dicionarios: tabelas de Hash  |
| 3.Nov a 7.Nov    | Ficha 3.1 (min-heaps)                 | Árvores AVL: motivação e algoritmo de inserção balanceada           |
| 10.Nov a 14.Nov  | Revisões                              | Revisões                                                           |
| 17.Nov a 21.Nov  | Ficha 3.2 (THash)                     | Grafos: representações e funções de consulta                       |
| 24.Nov a 28.Nov  | Ficha 4.1 (Representações de grafos)  | Grafos: travessias                                                 |
| 1.Dez a 5.Dez    | Ficha 4.2 (Travessias de grafos)      | Grafos pesados: algoritmo de Dijkstra, Prim e Floyd Warshal        |
| 8.Dez a 12.Dez   | Ficha 4.3 (Grafos pesados/problema)   |                                                                    |

<br>
# Avaliação

Será constituída por dois testes nas seguintes datas:
* 15 Novembro 2025
* 10 Janeiro 2026

O exame de recurso será no dia 24 Janeiro 2026.



<br>
# Material 

### Notas/slides JSP

* [C1. Especificação e Correcção de Algoritmos](https://www.dropbox.com/scl/fi/si8rl0wnpramf3k140jp3/C1.-Especifica-o-e-Correc-o-de-Algoritmos.pdf?rlkey=c8gwl9aiax8j5xsowtv4f96o4&dl=0)
* [C2. Correcção de Algoritmos com Ciclos](https://www.dropbox.com/scl/fi/9ggkdd9cz79olsgdz9enr/C2.-Correc-o-de-Algoritmos-com-Ciclos.pdf?rlkey=2ilvstmmtyxpgij6v6inttbs5&dl=0)
* [T1. Tempo de Execução de Algoritmos Iterativos](https://www.dropbox.com/scl/fi/argncz6lpdxaiaqjhfgjy/T1.-Tempo-de-Execu-o-de-Algoritmos-Iterativos.pdf?rlkey=khrabx7fvoi0qddpuqch29cpz&dl=0)


### Notas JBB

* [Correcção de Algoritmos](./Correccao.pdf)


<br>
# Contactos

  | Docente         | Horário Atendimento |
  | ----------      |------------ |
  | [José Bacelar Almeida](mailto:jba@di.uminho.pt)  | 5a-f, 11h00-13h00 |
  | [José Bernardo Barros](mailto:jbb@di.uminho.pt)  | 3a-f tarde |
  | [Renato Neves](mailto:nevrenato@di.uminho.pt)    | 3a-f tarde |
  | [Jorge Sousa Pinto](mailto:jsp@di.uminho.pt)     | 6a-f, 9h00-11h00 |



<br>
# Bibliografia

Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, and Clifford Stein. Introduction to Algorithms, Fourth Edition. The MIT Press, 2022. 

Donald E. Knuth. The Art of Computer Programming, Volume I: Fundamental Algorithms, 2nd Edition. Addison- Wesley, 1973. 

Donald E. Knuth. The Art of Computer Programming, Volume III: Sorting and Searching. Addison-Wesley, 1973. 

Donald E. Knuth. The Art of Computer Programming, Volume II: Seminumerical Algorithms, 2nd Edition. Addison- Wesley, 1981. 

Robert Sedgewick, Kevin Wayne. Algorithms. Addison-Wesley, 4th edition (March 24, 2011).
