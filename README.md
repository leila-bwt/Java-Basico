## Bootcamp Java - Santander || Dio

Trilha de Back-end Java do Santander Bootcamp 2024! Aprenda desde os primeiros passos com Java partindo da sintaxe básica até a implementação de uma API utilizando Spring.

### Fundamentos

Java Básico

A linguagem Java é comnposta por um cnjunto bem definido de funcionalidades (features) que são super recomendadas conhecer o máximo que puder.

Vamos explorar algumas dessas 'feature':

Simples
Java é uma linguagem de programação simples e fácil de entender, pois não contém complexidade que existiam em linguagens de programação anteriores. Na verdade, a cimplicidade era o objetivo do design dos povos Javasoft, porque ele tem que funcionar em dispositivos eletrônicos onde menos memória/recursos estão disponíveis.

Orientada a Objeto
Java é uma linguagem de Programação Orientada a Objetos. Isso significa que em Java tudo é escrito em termos de CLASSES e OBJETOS.

Para começar a desenvolver softwares de forma consistente com Java, é necessário compreender os pilares da Programação Orientada a Obejtos (POO). Eles são:

1. Classe e Obejto
2. Encapsulamento
3. Abstração
4. Herança
5. Polimorfismo

Plataforma independente
O objetivo de design do javasoft people é desenvolver uma linguagem que funcione em qualquer plataforma. Uma plataforma é um ambiente de hardware ou software no qual um programa é executado.

Em Java, o código fonte é complilado para bytecode e esse bytecode não está vinculado a nenhuma plataforma.

Portátil
O conceito WORA (Write Onde Run Anywhere) e o recurso independente de plataforma tornam o Java portátil. Agora, usadno a linguagem de programação Java, os desenvolvedores podem obter o mesmo resultado em qualquer máquina, escrevendo o código apenas uma vez. A razão por trás disso é JVM e bytecode.

Robusta
A linguagem de programação Java é robusta, o que significa que é capaz de lidar com o encerramento inesperado de um programa.
>Ele usa um gerenciamento de memória forte
>Java fornece coleta de lixo automática
>Há tratamento de exceção e mecanismo de verificação de tipo em Java.

Segura
Problemas como ameaças de vírus, adulteração, espionagem ou representação de aplicativo usando Java também precisa de algum tipo de segurança. Por isso, a linguagem também fornece recursos de segurança para os programadores. Também existem Recursos de criptografia e descriptografia para protreger seus dados contra espionagem e adulteração na Internet.

Interpretada
Nas linguagens de programação, você aprendeu que eles usam o compilador ou interpretador, mas a linguagem de programação Java usa os dois. Os programas Java são compilados para gerar arquivos de bytecode e a JVM (Java Virtual Machine) interpreta o arquivo de bytecode durante a execução.

Multi-thread
Thread é um subprocesso leve e independente de um programa em execução (ou seja, processo) que compartilha recursos. Multi-threading é o nome dado ao processo de vários threads sendo executados simultaneamente.


## Aula 1

Apresentar as regras essenciais para a construção de códigos com base na linguagem Java.

A escrita de códigos de um programa é feito através da composição de palavras pré-definidas pela linguagem com as expressões que utilizamos para determinar o nome dos nossos arquivos, classes, atributos e métodos.

É muito comum mesclarmos expressões no idioma americano com o nosso vocabulário. Existem projetos que recomendam que toda a implementação do seu programa seja escrita na língua inglesa.

## Aula 2 - Padrão de nomenclatura

Quando se trata de escrever códigos na linguagem Java, é recomendado seguir algumas convenções de escrita. Esses padrões estão expressos nos itens abaixo:

* Arquivo .java: Todo arquivo .java deve começar com letra MAIUSCULA. Se a palavra for composta, a segunda palavra deve também ser maiúscula.

* Nome da classe no arquivo: A classe deve possuir o mesmo nome do arquivo.java

* Nome de variável: toda variável deve ser escrita com eltra minuscula, porém se a palavra for composta, a primeira letra da segunda palavra deverá ser maiuscula - "camelCase".

>Regras da linguagem para declarar uma variável:
>* Deve conter apenas letras, _(underline), $ ou os números de 0 a 9
>* Deve obrigatóriamente se iniciar por uma letra (preferencialmente), _ou $, jamais com número
>* Deve iniciar com uma letra minúscula (boa prática)
>* Não pode conter espaços
>* Não podemos usar palavras-chave da linguagem
>* O nome deve ser único dentro de um escopo  

## Aula 3 - Declarando variáveis e métodos

Declarar uma variável em Java segue a seguinte estrutura:

Tipo NomeBemDefinido = Atribuição (opcional em alguns casos)

## Aula 4 - Identação
Basicamente indentar é um termo utilizado para escrever o código do programa de forma hierárquica, facilitando assim a visualização e o entendimento do programa.

## Aula 5 - Organizando arquivos
A medida que nosso sitema vai evoluindo, surgem novos arquivos (código fonte) em nossa estrutura de arquivos do projeto. Isso exige que seja realizado uma organização destes arquivos através de pacotes (packages).

## Aula 6 - Java Beans
Uma das maiores dificuldades na programação é escrever algoritmos legíveis a níveis que sejam compreendidos por todo seu time ou por você mesmo no futuro. Para isso a linguagem Java sugere, através de convenções, formas de escrita universal para nossas classes, atributos, métodos e pacotes.

>Variáveis
Mais cedo já aprendemos algumas regras de declaração de variáveis, mas agora iremos conhecer algumas sugestões de nomenclatura:

>>Uma variável deve ser clara, sem abreviações ou definição sem sentido;
>>Uma variável é sempre no singular, exceto quando se referir a um array ou coleção;
>>Defina um idioma único para suas variáveis. Se você for declarar variáveis em inglês, defina todas em inglês.

>Métodos
Deverão ser nomeados como verbos + ação, através de uma mistura de letras minúsculas e maiúsculas. Em principio todas as letras que compõem o nome devem ser mantidas em minúsculo, com exceção da primeira letra de cada pavra composta a partir da segunda palavra.


## Aula 7 - Tipo e Variáveis
Explorar os tipos de dados numéricos inteiros, numéricos decimais, lógicos, caracteres e suas aplicabilidades.
Explicar a diferença entre definição de variáveis e constantes.