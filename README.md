# Template-Method

O padrão de Template - Method de modelo é um padrão de design comportamental amplamente aceito para impor algum tipo de algoritmo (conjunto fixo de etapas) no contexto da programação.
Ele define as etapas sequenciais para executar um algoritmo de várias etapas e, opcionalmente, pode fornecer uma implementação padrão também (com base nos requisitos).

Aplicaçao padrao Template-Method

-Quando temos etapas pré-definidas para alcançar algum algoritmo.

-Quando queremos evitar a duplicação de código, movendo a implementação comum e as etapas na classe base.

Exemplo diagrama de classe:

![alt text](https://howtodoinjava.com/wp-content/uploads/2017/06/template-design-pattern-class-diagram.gif)

Exemplo de aplicação

Construir qualquer casa que geralmente tenha certas etapas. Algumas etapas têm implementação padrão e algumas etapas são muito específicas para o implementador, sem implementação padrão.

Etapas com implementação padrão

-Construção da fundação de base

-Construção de telhado

-Etapas com implementação padrão “NÃO”

-Construção de paredes

-Construção de janelas e portas

-Pintura

-Decoração interior

-Queremos aplicar essas etapas sequencialmente por todas as classes de implementação no aplicativo.


Solução

No problema acima, temos certos passos em ordem fixa que todas as classes de construção devem seguir. Portanto, podemos usar o padrão de design de método de modelo para resolver esse problema.

Vamos definir uma classe base House que terá todas as etapas como métodos e um método buildhouse () de modelo que chamará as etapas intermediárias - sequencialmente.

Também criaremos classes derivadas com base no tipo de casas, como GlassWallHouse e ConcreteWallHouse.

Nos arquivos deste repositório, temos códigos de exemplo implementando o padrão em JAVA.



