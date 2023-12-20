# Trabalho Prático 2 

## Grupo 7

| Aluno                  | Matrícula |
| ---------------------- | --------- |
| Josué Teixeira Santana | 202029012 |
| Abdul hannan           | 202045624 |
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





## Simplicidade 

A simplicidade no design de software é a arte de criar soluções claras e facilmente compreensíveis, evitando complexidades desnecessárias. Este princípio busca aprimorar a estrutura do código, proporcionando benefícios tangíveis à sua organização e legibilidade. A busca pela simplicidade resulta em códigos concisos e diretos, contribuindo para uma manutenção eficiente e redução de erros.

### Efeitos no Código

 - Estrutura Clara e Organizada: A simplicidade promove uma estrutura de código mais lógica e bem organizada. Ao decompor tarefas complexas em componentes menores e gerenciáveis, cria-se uma arquitetura modular que facilita a navegação no código-fonte.
 - Facilidade de Leitura e Compreensão: Um código simples é mais legível, favorecendo a compreensão por parte de outros desenvolvedores. Essa característica é crucial em projetos de equipe, onde diferentes pessoas interagem com diferentes partes do código.
 - Redução da Duplicação de Código: A busca pela simplicidade identifica e elimina redundâncias, reduzindo a duplicação de código. Isso resulta em código mais conciso, fácil de manter e menos suscetível a erros.
 - Coesão Melhorada: A simplicidade fortalece a coesão entre os componentes do software. Ao definir responsabilidades específicas para cada módulo, facilita-se a manutenção e a modificação do código.
 - Baixo Acoplamento: A simplificação do código contribui para um menor acoplamento entre os módulos do software. Isso permite alterações em componentes específicos sem impactar todo o sistema, conferindo flexibilidade e adaptabilidade.
 - Facilidade de Testes: Códigos simples são mais fáceis de testar, pois suas funcionalidades estão bem definidas e isoladas. Testes de unidade e integração tornam-se mais simples e eficazes.
 - Facilidade de Depuração: Em códigos simples, é mais fácil identificar a origem de bugs, pois a lógica é clara e a complexidade é reduzida.
 - Facilidade de Manutenção e Evolução: A simplicidade torna a manutenção e evolução do software mais eficientes. Novas funcionalidades podem ser implementadas de forma rápida e menos propensa a causar problemas inesperados.

### Relação com Maus-Cheiros de Código (Fowler)

A simplicidade, ao ser incorporada no desenvolvimento, aborda diversas preocupações identificadas por Martin Fowler como "maus cheiros" de código:

 - Duplicação de Código: A simplicidade visa eliminar duplicações, reduzindo redundâncias e melhorando a manutenibilidade do código.
 - Métodos Longos: Ao buscar simplicidade, métodos longos são quebrados em unidades menores e mais coesas, melhorando a clareza e facilitando a manutenção.
 - Classes Grandes: A busca pela simplicidade incentiva a criação de classes mais específicas e encapsuladas, evitando a complexidade desnecessária.
 - Muitos Parâmetros: A simplificação do código reduz a necessidade de muitos parâmetros, tornando as funções mais compreensíveis.
 - Métodos Complexos Condicionais: A simplicidade favorece a simplificação de expressões condicionais complexas, melhorando a legibilidade.
 - Dependências Desnecessárias: A busca pela simplicidade reduz o acoplamento desnecessário entre classes, promovendo uma estrutura mais modular.
 - Código Pouco Claro: A simplicidade combate a falta de clareza, promovendo uma escrita de código mais compreensível.
 - Comentários Desnecessários: Um código simples muitas vezes elimina a necessidade de comentários excessivos, pois sua clareza intrínseca facilita a compreensão.
 - Classes com Muitas Responsabilidades: A busca pela simplicidade resulta em classes mais focadas e específicas, evitando o acúmulo de responsabilidades.




## Modularidade

A modularidade é uma prática fundamental em projetos de software, caracterizada pela divisão do código em módulos independentes, cada um com uma responsabilidade clara e bem definida. Esses módulos, ao serem combinados, formam a base de sistemas complexos, proporcionando diversos benefícios à estrutura do código e à sua qualidade geral.

### Efeitos no Código

A modularidade contribui para uma estrutura organizada e gerenciável do código. Ao dividir o sistema em unidades lógicas, cria-se uma arquitetura que facilita a leitura, manutenção e compreensão do código. A abordagem modular resulta em blocos de construção independentes, promovendo a reusabilidade e simplificando o desenvolvimento.

 #### Impacto na Claridade e Compreensão:
 
   - Módulos independentes tornam o código mais claro e compreensível. Cada módulo representa uma unidade coesa de funcionalidades, permitindo que os desenvolvedores se concentrem em partes específicas do sistema sem se perderem em detalhes desnecessários. Isso melhora a legibilidade do código e facilita o compartilhamento de conhecimento entre membros da equipe.

#### Coesão e Acoplamento:

   - A alta coesão, característica intrínseca à modularidade, significa que cada módulo contém funcionalidades relacionadas, evitando fragmentação e dispersão de lógica. Em contrapartida, o baixo acoplamento entre módulos minimiza as dependências, tornando o código mais flexível. Mudanças em um módulo têm impacto limitado em outros, reduzindo a propagação de efeitos colaterais não intencionais.

### Relação com Maus-Cheiros de Código (Fowler)

A modularidade atua como um antídoto para vários maus-cheiros identificados por Fowler. Em particular, a "Mudança Divergente" é combatida pela clara definição de responsabilidades em cada módulo. Quando uma alteração no código exige modificações em várias partes do sistema, isso pode ser um sinal de falta de modularidade. Ao manter módulos independentes e coesos, a modularidade reduz a propensão a este mau-cheiro.
Em suma, a modularidade não é apenas uma prática de design, mas uma abordagem que molda a estrutura, claridade, coesão e acoplamento do código, promovendo um desenvolvimento de software mais eficiente e sustentável.










## Referências Bibliográficas
- Livro "Refactoring: Improving the Design of Existing Code" de Martin Fowler
- Artigo "The Importance of Simplicity in Software Development" de Robert C. Martin
