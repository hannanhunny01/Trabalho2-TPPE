# Trabalho Prático 2 

## Grupo 7

| Aluno                  | Matrícula |
| ---------------------- | --------- |
| Josué Teixeira Santana | 202029012 |
| Abdul hannan           | 202045624 |
| Luís Guilherme         | 180022962 |
| Victor Eduardo         | 190038926 |
| Levi Queiroz           | 170108341 |
| Heitor Marques         | 202016462 |

## Extensibilidade

A extensibilidade é uma característica de um sistema de software que permite que ele seja facilmente adaptado a novas necessidades ou mudanças. Em termos de estrutura, a extensibilidade geralmente envolve a criação de componentes modulares e de baixo acoplamento, permitindo que as partes do sistema sejam modificadas ou estendidas sem afetar outras partes.

### Efeitos no código

A extensibilidade tem os seguintes efeitos no código:

- Estrutura: A extensibilidade geralmente resulta em uma estrutura modular, onde as funcionalidades são organizadas em componentes independentes e reutilizáveis. Isso facilita a compreensão e a manutenção do código.
- Claridade: Componentes extensíveis são projetados para serem facilmente compreensíveis e modificáveis. Isso envolve o uso de nomes descritivos, separação clara de responsabilidades e um design limpo.
- Coesão: A extensibilidade tende a promover a alta coesão, onde cada componente é responsável por uma única tarefa ou conjunto de tarefas relacionadas. Isso melhora a modularidade e facilita a manutenção do código.
- Acoplamento: A extensibilidade busca reduzir o acoplamento entre os componentes, permitindo que eles sejam estendidos ou substituídos sem afetar outras partes do sistema. Isso resulta em um código mais flexível e menos propenso a efeitos colaterais indesejados.

### Relação com os maus cheiros definidos por Fowler

Os "maus cheiros de código" são padrões ou práticas de programação que indicam a presença de problemas ou deficiências no código-fonte. A extensibilidade pode ajudar a mitigar ou evitar muitos desses maus-cheiros, pois um código extensível é projetado com foco na manutenção e em evitar armadilhas comuns.

Por exemplo, um mau-cheiro comum é a "Classe Deus" (God Class), que é uma classe que realiza muitas tarefas diferentes e tem muitas responsabilidades. A extensibilidade pode ser usada para dividir essa classe em componentes menores e mais focados, melhorando a coesão e tornando o código mais modular e fácil de entender.

### Operação de refatoração para alcançar a extensibilidade

Uma operação de refatoração que pode ajudar a tornar um projeto de código mais extensível é a "Extração de Método" (Extract Method). Essa operação envolve a identificação de blocos de código repetitivos ou lógica complexa e a extração desses trechos em métodos separados e reutilizados.

Ao extrair métodos, você pode criar componentes independentes que podem ser estendidos ou substituídos individualmente, melhorando a extensibilidade geral do código. Além disso, a extração de métodos pode melhorar a clareza e coesão do código, tornando-o mais legível e fácil de manter.

## Referências Bibliográficas
- Livro "Refactoring: Improving the Design of Existing Code" de Martin Fowler
- Artigo "The Importance of Simplicity in Software Development" de Robert C. Martin