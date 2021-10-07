# Qual a produtividade do ponto de função para estimar esforço

### O mito da Tabela de Produtividade do Ponto de Função para Estimar o Esforço

Na busca por uma resposta por qual a produtividade do ponto de função para estimar o esforço, o mais comum é procurar uma Tabela de Produtividade com a quantidade de HH (homem-hora) / PF (Ponto de Função). Como por exemplo a Tabela de Produtividade a seguir obtida do [Roteiro de Contagem do SERPRO](http://www.pgfn.fazenda.gov.br/acesso-a-informacao/tecnologia-da-informacao/Roteiro_Contagem_PF_SERPRO_ 7.pdf):

Pesquisar

| Plataforma de Desenvolvimento | Baixa | Média | Alta |
| :---------------------------- | :---- | :---- | :--- |
| ACCESS                        | 10    | 8     | 6    |
| ASP                           | 16    | 11    | 6    |
| ASPNET                        | 11    | 8     | 5    |
| ASSEMBLER                     | 18    | 12    | 8    |
| BASIC                         | 18    | 12    | 8    |
| C                             | 24    | 18    | 12   |
| C#                            | 17    | 12    | 7    |
| C++                           | 18    | 12    | 8    |
| CKAN                          | 18    | 14l8  |      |
| CLIPPER                       | 12    | 8     | 6    |

Mostrando de 1 até 10 de 64 registros

AnteriorPróximo

### A desconstrução da Tabela de Produtividade

Inicialmente, você pode perceber haver alguns problema no uso dessa Tabela de Produtividade dificultando a sua utilização.

Por exemplo, coloque no campo de pesquisa o texto “WebService”. Veja que se apresenta um resultado com uma taxa de entrega entre 26 HH / PF e 12 HH / PF com uma taxa de entrega média de 19 HH / PF.

O que isso quer dizer?

Por exemplo, se elementos da arquitetura que suporta funcionalidades do usuário utilizam-se de webservices, então esses elementos da arquitetura devem ser medidos como funções e o esforço apropriado de maneira direta ao estimar o esforço?

Claro, que não.

Em seguida, coloque no mesmo campo Java. Observe, que em resposta lhe é apresentado um resultado com sete classes. Se um desenvolvimento envolve a codificação do front-end usando Java Script e o back-end usa Java, então eu devo ter duas medições: uma para o front-end e cujo esforço é estimado com a taxa de entrega do Java Script e outra para o back-end e cujo esforço é estimado com a taxa de entrega do Java?

Claro, que não.

Por fim, o que está incluído nessas horas componentes do indicador de produtividade; ou seja nas horas / ponto de função? Em outros termos qual o escopo de atividade incluído? Variações nesse escopo de atividades podem explicar as diferenças, que apenas pela tecnologia de desenvolvimento não se explica.

### Estimativa e preço e a Tabela de Produtividade

Um artigo bastante relacionado à Tabela de Produtividade do Ponto de Função para Estimar o Esforço é sobre o preço do ponto de função. Se quiser mais informações não deixe de consultar o material a seguir:

[Análise de Pontos de Função](https://www.fattocs.com/categoria/analise-de-pontos-de-funcao/)

### [Qual o preço do ponto de função (ou quanto custa)](https://www.fattocs.com/blog/qual-o-preco-do-ponto-de-funcao/)

A avaliação do preço do ponto de função varia desde uma lógica simplista, como se o ponto de função fosse um papel na bolsa de valores, até uma análise complexa envolvendo a avaliação dos vários fatores afetando o preço do ponto de função. A decisão sobre qual direção tomar na avaliação do preço do ponto de função é uma decisão sobre o nível de risco ao qual se está disposta assumir.

[Leia mais](https://www.fattocs.com/blog/qual-o-preco-do-ponto-de-funcao/)

### *Benchmarking* Externo

O [ISBSG (*International Software Benchmarking Standards Group*)](http://www.isbsg.org/) é uma das principais fontes de referência sobre a produtividade em pontos de função. No entanto, usar essas fontes desconsiderando o contexto de como aqueles números foram obtidos e o contexto de sua própria organização é um erro grave. Estimativas obtidas dessa maneira dificilmente terão a confiabilidade necessária ou alguma utilidade prática.

A melhor forma de obter indicadores de produtividade que realmente sejam úteis nas estimativas com pontos de função é apurar esse indicador através dos projetos desenvolvidos pela organização. Mas como fazer isto?

### *Benchmarking* Interno

O primeiro passo é recuperar dos desenvolvimento passados as duas grandezas que compõe o indicador de produtividade: o tamanho (em pontos de função) e o esforço (horas). Com estes dois dados, tem-se de forma direta a produtividade daquele desenvolvimento. Mas se cada desenvolvimento tiver um número de produtividade diferente, qual deve ser empregado no projeto a ser estimado?

Certamente que cada desenvolvimento pode apresentar um número distinto, mas se este procedimento for repetido para um conjunto maior de projetos será possível observar que para determinados subconjuntos a produtividade é bastante similar. Isso acontece quando os projetos tem características similares em relação aos fatores que afetam diretamente o esforço para desenvolvê-los. Logo, é razoável concluir que dependendo da natureza dos projetos desenvolvidos pela organização, não haverá um único indicador de produtividade para todos os projetos da organização; mas sim indicadores de produtividade por grupos de projeto similares. Sendo assim, o primeiro passo para estimar um novo projeto é enquadrá-lo em algum grupo de projetos e só então usar o indicador de produtividade adequado. Mas quais são os fatores que definem esses grupos de projetos?

### Fatores afetando a produtividade

Qualquer variável que tenha capacidade de produzir um impacto significativo no esforço do projeto deve ser levada em consideração nessa análise de segmentação de grupos de projeto. Convém destacar que os fatores podem ser diferentes de organização para organização. Por exemplo: o uso ou não de uma determinada metodologia de desenvolvimento de sistemas no projeto pode afetar sua produtividade. No entanto se em uma determinada empresa todos os projetos seguem a mesma metodologia, este fator será constante e não terá relevância para a segmentação de projetos.

Sem a pretensão de estabelecer uma lista completa, pode-se citar os seguintes fatores:

– tipo de projeto: desenvolvimento, melhoria, migração, redesenvolvimento, etc;
– plataforma tecnológica: mainframe, web, cliente x servidor, sistema embutido, etc;
– ordem de grandeza dos projetos;
– tamanho da equipe de desenvolvimento;
– ferramentas de desenvolvimento;
– metodologia empregada;
– área de negócio;
– número de usuários.

### Conclusão

De forma análoga ao [preço por ponto de função](https://www.fattocs.com/blog/qual-o-preco-do-ponto-de-funcao/), estimar o esforço a partir da medição ou [aproximação do tamanho em pontos de função](https://www.fattocs.com/analise-de-pontos-de-funcao/contagem-antecipada-de-pontos-de-funcao/) está intimamente ligado aos [níveis de risco](https://www.fattocs.com/cursos/estimativas-de-software/), que se tolera assumir.