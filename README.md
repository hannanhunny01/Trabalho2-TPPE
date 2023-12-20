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









## Ausência de Duplicidades

A ausência de duplicidades é um atributo essencial em código de qualidade, fundamentado no princípio de evitar redundâncias desnecessárias. A detecção de duplicidades indica a repetição de lógica, expressões ou funcionalidades em diversos locais do código, abrangendo desde funções e classes até fragmentos mais pequenos de código.

### Efeitos no Código:

 - Estrutura: A eliminação de duplicidades aprimora a estrutura do código, evitando a fragmentação da lógica em várias partes e fomentando uma organização mais coesa e concisa.
 - Claridade: A ausência de duplicidades resulta em um código mais claro e de fácil compreensão, pois os desenvolvedores não precisam buscar e entender múltiplas instâncias de uma mesma lógica.
 - Eficiência: A reutilização de código reduz o tamanho do programa, contribuindo para um código mais enxuto e gerenciável.
 - Manutenção: Quando alterações são necessárias, a ausência de duplicidades implica fazer a modificação em um único local, aumentando a produtividade e diminuindo a chance de erros.
 - Coesão: A eliminação de duplicidades fortalece a coesão do código, concentrando a lógica em um local central e tornando o comportamento de funções ou classes mais consistente.
 - Acoplamento: A redução de duplicações também pode levar a um menor acoplamento entre diferentes partes do código, uma vez que a funcionalidade compartilhada é centralizada.

### Relação com Maus-Cheiros de Código (Fowler):

Relação com maus cheiros de código: A ausência de duplicidades está intrinsecamente ligada à eliminação do mau cheiro de "Código duplicado", abordando soluções para evitar repetições desnecessárias de trechos de código.

Operação de refatoração: A técnica amplamente utilizada, como a operação de refatoração Extract Method, destaca-se como uma abordagem eficaz para eliminar duplicidades. Identificar trechos duplicados e extrair essas partes para um método separado promove a reutilização de código, melhora a manutenibilidade e evita erros resultantes de alterações inconsistentes.

Em resumo, a ausência de duplicidades não é apenas um princípio de desenvolvimento de software, mas uma prática que eleva a qualidade do código, facilita a manutenção e promove a construção de sistemas mais eficientes e robustos. Incorporar essa filosofia no desenvolvimento de software é fundamental para garantir soluções sólidas e sustentáveis a longo prazo.



















## Referências Bibliográficas
- Livro "Refactoring: Improving the Design of Existing Code" de Martin Fowler
- Artigo "The Importance of Simplicity in Software Development" de Robert C. Martin
