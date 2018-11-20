# Modelo Cascata

O modelo cascata é utilizado principalmente quando os requisitos de um determinado
problema são bem compreendidos. Uma forma de utilizar o modelo cascata é quando precisamos
fazer adaptações ou aperfeiçoamentos em um sistema já existente. Por exemplo, quando
temos um sistema já pronto e precisamos fazer uma adaptação porque alguma lei governamental
foi alterada ou criada.
Também podemos utilizar o modelo cascata quando um software necessita de uma nova funcionalidade e os requisitos estão bem definidos e são estáveis.
O modelo cascata também é chamado de ciclo de vida clássico ou tradicional.
Este modelo sugere uma abordagem sequencial e sistemática para o desenvolvimento de software. Dessa forma, começamos com o levantamento
de requisitos ou necessidades junto ao cliente, depois vamos para a fase de planejamento onde definimos estimativas, cronograma e acompanhamento, após isso partimos para a modelagem
onde fazemos a análise e projeto, seguindo da construção onde codificamos e testamos, passamos para a implantação ou emprego onde efetuamos a entrega, suporte e feedback do software concluído.
Basicamente na etapa de levantamentos de requisitos ou necessidades estabelecemos junto aos clientes os requisitos do produto desejado pelo cliente
que consiste dos serviços que devem ser fornecidos, limitações e objetivos do software. Esta etapa também consiste da documentação e o estudo de viabilidade do projeto para determinarmos o processo de inicio de desenvolvimento do projeto do sistema. Na etapa de planejamento temos a definição de estimativas, cronograma e acompanhamento baseando-se nos requisitos e na determinação das tarefas que, por sua vez, são determinadas pelos requisitos. A etapa de modelagem é uma prévia da próxima etapa de construção, nesta etapa define-se a estrutura de dados, arquitetura do software, interfaces, etc. A etapa de construção abrange a implementação, onde os programas são efetivamente criados e também os testes que é onde se testam as lógicas internas do software e as funcionalidades externas. As funcionalidades internas normalmente são realizadas com o uso de testes unitários e as fases externas podem ser realizadas por testadores e pelo próprio cliente. Por fim, a etapa de emprego ou implantação abrange e entrega efetiva do software no cliente que é onde instalamos o software no servidor ou na máquina do cliente junto com outros utilitários como banco de dados ou outros itens dependendo do software sendo construído. O suporte é onde tiramos dúvidas dos clientes e a manutenção consiste na correção de erros que não foram previamente detectados.

A figura abaixo demonstra as etapas discutidas acima.   


![Imagem do DevMedia](https://i.imgur.com/coI72OP.png)

## 1. Fase de Requerimentos:   
Nesta fase são estabelecidos os requisitos do produto que o idealizador almeja desenvolver, o que normalmente se baseia nos serviços que precisam ser fornecidos, nas limitações aceitáveis e os objetivos do software.

Depois que isso é determinado, os requisitos precisam ser estabelecidos de uma forma adequada para que também sejam úteis para a próxima etapa. Esta fase compreende a documentação e o estudo da viabilidade e a facilidade do projeto com a finalidade de estipular o processo de inicio de desenvolvimento do projeto do sistema, podendo ser estendida como o começo do ciclo de vida do produto.

## 2. Projeto do Sistema:

O projeto de elaboração do sistema é composto por vários processos que se centralizam em quatro atributos diferentes do sistema, sendo: a estrutura de dados, a arquitetura do software, caracterização das interfaces e detalhes procedimentais.

O processo de projeto mostra os requisitos de uma maneira que possibilita a codificação do produto (sendo uma prévia fase de codificação). Da mesma forma que a análise dos requisitos, o projeto passa a ser documentado e torna-se parte do software.

## 3. Implementação:

A etapa de implementação é quando os programas são criados. Caso o projeto tenha um nível de detalhamento mais avançado, a etapa de codificação pode ser implementada de maneira automática.

A princípio, é recomendado adicionar um teste unitário de cada módulo que é desenvolvido nesta fase. Nesta situação, as unidades de código criadas são submetidas a testes individuais antes de progredir para a etapa de integração e teste global.

## 4. Teste do Sistema

Após o fim da etapa de codificação, inicia-se a fase da realização de teste do sistema. Este processo de teste é focado em dois pontos principais, que são as lógicas internas do software e as suas funcionalidades externas.

Esta etapa é importante porque evidencia se os erros de comportamento do software foram solucionados e assegura que as entradas definidas produzam resultados eficientes e que estão de acordo com os requisitos determinados anteriormente.

## 5. Manutenção

A fase da manutenção se baseia na correção de erros que não detectados durante os testes, em melhorias funcionais e de preferência com os demais tipos de suporte. Esta etapa faz parte do ciclo de vida do produto de software e não pertence apenas ao seu desenvolvimento. As melhorias e alterações para correções do software podem ser classificadas como parte do processo de desenvolvimento.

As etapas de manutenção descritas até agora são as mais importantes e utilizadas, mas também existe as sub-etapas que devem ser executadas dentro de cada etapa, que podem se diferenciar do desenvolvimento de um projeto para o outro.

Além disso, também pode acontecer de alguns projetos de softwares precisarem da incorporação de uma fase extra ou a separação de uma etapa em outras etapas para ampliar a organização.

Por fim, pode-se dizer que todas as variações do modelo cascata contam com o mesmo conceito básico, que é a ideia de uma etapa oferecer a saída que serão utilizadas como entrada para a próxima etapa.

Sendo assim, o processo de desenvolvimento de um produto de software de acordo com as características do modelo cascata é mais simples de entender e controlar.

Outras ações que também precisam ser levadas em consideração em todas as etapas que fazem parte do desenvolvimento do software por meio do modelo cascata são a documentação, a verificação e a administração das etapas.

Neste caso, a documentação é exigida para que uma etapa disponibilize os dados corretos para a próxima fase.  Enquanto que a administração desempenha o papel de efetuar a gestão e o controle da etapa.

### Vantagens:
* Torna o processo de desenvolvimento estruturado. Tem uma ordem sequencial de fases. Cada fase cai em cascata na próxima e a anterior necessita estar terminada antes do inicio da seguinte.
* Todas as atividades identificadas nas fases do modelo são fundamentais e estão na ordem certa.

### Desvantagens:

* Não fornece feedback entre as fases e não permite a atualização ou redefinição nas fases anteriores.
* Não suporta modificações nos requisitos.
* Não prevê a manuntenção.
* Não permite a reutilização.
* É excessivamente sincronizado.
* Se ocorre um atrasado todo o processo é afetado.
* Lançamento do software inicial muito tarde.







Bibliografia:

[1] Pressman, R. Engenharia de Software: Uma abordagem Profissional. 7º edição. Editora Bookman.                 
