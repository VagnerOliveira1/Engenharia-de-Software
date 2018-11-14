
# Modelo V de Desenvolvimento

## **Definição**

O **Modelo V** é um modelo conceitual de Engenharia de Sistemas/Desenvolvimento de Produto visto como melhoria ao problema de reatividade do [**modelo em cascata**](https://pt.wikipedia.org/wiki/Modelo_em_cascata). Ele permite que, durante a integração de um sistema em seus diversos níveis, os testes sejam feitos contra os próprios requisitos do componente/interface que está sendo testado(a), em contraste com modelos anteriores onde o componente era testado contra a especificação do componente/interface. Notar a diferença entre requisito e especificação.


O **Modelo V** virou um padrão da indústria de <i>software</i> depois de 1980 e, após o surgimento da [**Engenharia de Sistemas**](https://pt.wikipedia.org/wiki/Engenharia_de_Sistemas), tornou-se um conceito padrão em todos os domínios da indústria. O mundo do <i>software</i> tinha feito poucos avanços em termos de maturidade, em achar na bibliografia corrente as referências que poderiam se 
aplicar ao sistema.

Um ponto relevante quando se está desenvolvendo software é decidir quando testar e como testar o software ou as partes geradas ao longo de seu desenvolvimento. A escolha do escopo do teste e o momento de aplicar estes testes é muito importante.

O escopo do teste indica o que é de interesse testar, que pode ser desde o código, uma classe, uma função, um pacote, um serviço ou todo o sistema. Estas escolhas estão normalmente associadas a diferentes fases dos testes: unidades, os testes de integração, os testes sistema e os testes de aceitação.

Estas fases estão mais visíveis na **Figura 1**, que exemplifica como elas podem ser encontradas em um processo de software.

 ![Figura 1 Modelo V ](https://arquivo.devmedia.com.br/REVISTAS/es/imagens/72/8/1.png) <center>**Figura 1**. Modelo “V” (Fases do Desenvolvimento X Fases dos Testes)</center> <center>Fonte: Devmedia</center>

## **Características**

 - Enfatiza a importância de considerar as atividades de testes durante o processo, ao invés de um teste posterior após o término do processo;
- Pode-se obter a retroalimentação mais rapidamente;
 - Ajuda a desenvolver novos requisitos;
 - Melhora a qualidade do produto resultante.

- Os testes têm resultados de maior efetividade, uma vez que são testados contra requisitos e não contra especificações;
- Este modelo possibilita que se encontre erros durante os processos de se derivar especificações de requisitos;
- Melhora a qualidade do produto resultante, uma vez que valida o processo de engenharia de sistemas durante a integração do sistema.

## **Vantagens**


 - Simples e fácil de usar. Testando atividades como planejamento, teste de concepção, simulações bem antes da construção. Isso economiza muito tempo. Daí a maior chance de sucesso sobre o modelo em cascata (waterfall model);
- Rastreamento de defeitos pró-ativa, isto é os defeitos são encontrados em fase inicial;
- Evita o fluxo descendente dos defeitos;
- Funciona bem para pequenos projetos onde os requisitos são facilmente compreendidos;

## **Desvantagens**

 - Não considera o paralelismo que geralmente ocorre em projetos de maior complexidade;
- Não considera as diversas dimensões do projeto;
- Há ciclos de revisão em etapas tardias do processo, quando se encontra erros, sua correção é onerosa;
- Dificuldade em seguir o fluxo sequencial do modelo;
- Dificuldade para o cliente poder especificar os requisitos explicitamente;
- Se alguma mudança acontecer no meio do caminho, em seguida, os documentos de testes e analises, juntamente com os documentos de requisitos deverão ser atualizados;

## **Quando usar o modelo V:**

- O modelo em forma de V deve ser usado em projetos onde as exigências são claramente definidos e estabelecidos.

- O modelo em forma de V deve ser escolhido quando há recursos técnicos disponíveis (Especialistas, Softwares e Laboratórios) e com conhecimentos técnicos necessários para a realização (Processos e Procedimentos).

- Alta confiança nos processos de verificação e validação é necessário para escolher o modelo de abordagem em forma de V. Uma vez que, os protótipos são produzidos, pois simulações e analises virtuais devem ser aplicadas extensivamente no lado esquerdo do V. 
- Os testes físicos nos níveis de componentes e sistemas reduzem o risco envolvido na resposta às expectativas dos clientes durante a fase de teste de desempenho.


## **Etapas**

- Análise das necessidades e viabilidade;
- Especificação do *software*;
- Concepção: arquitetura; 
- Concepção: detalhamento;
- Codificação;
- Teste individual;
- Teste de integração;
- Teste de validação;
- Receita.

## **As várias fases do modelo-V, segue:**

Os **Requisitos** como BRS (***Business Requirements Specifications***) e SRS (***Sistem Requirements Specifications***) iniciam o ciclo de vida do modelo, assim como o "modelo em cascata" (***Waterfall model***). Mas, neste modelo antes que o desenvolvimento seja iniciado, um plano de **teste do sistema** (***DVP - Development Verification Plan***) deve ser criado. O plano de teste deve se concentrar em atender a funcionalidade especificada no levantamento dos requisitos. Conhecer as condições de uso da aplicação do produto (***Duty Cycle***) é essencial para o sucesso do projeto.  

A **fase de projeto de alto nível (HLD)** centra-se na arquitetura e design do sistema. É proporcionar visão geral de solução, plataforma, sistemas, produtos e serviço / processo. Um plano de **teste de integração** é criado nesta fase, a fim de testar as peças de sistemas e softwares verificando a capacidade para trabalhar em conjunto.

A **fase de projeto de baixo nível (LLD)** é o local onde os componentes são projetados e analisados. Ela define as características reais do projeto para cada um dos componentes do sistema. **Testes analíticos** e **simulações virtuais** dos componentes são criados e realizados nesta fase também.

A **fase de execução** inicia-se com a construção dos protótipos (base do Modelo-V). Uma vez que eles estão concluídos, o caminho de execução continua pelo lado direito do V onde os planos de testes desenvolvidos anteriormente são agora colocadas em prática. Testando fisicamente a **durabilidade** dos componentes em laboratório/bancadas, posteriormente testando o comportamento dos sistemas e subsistemas no mesmo ambiente controlado e por fim, validando o desempenho do produto final em condições de uso (aplicação real) e/ou em clientes e parceiros (**confiabilidade**).

![Figura 2 Modelo V ](https://www.guru99.com/images/6-2015/052715_0904_GuidetoSDLC3.png) <center>**Figura 2**. Diagrama do Modelo V</center> <center>Fonte: guru99</center>


## **Referências Bibliográficas**


1.	**Wikipédia**, 2018.
Disponível em: <<https://pt.wikipedia.org/wiki/Modelo_V#cite_note-2>>. Acesso em: 07 nov. 2018.

2.	**Wikipédia**, 2018. 
Disponível em: <<https://pt.wikipedia.org/wiki/Modelo_em_cascata>>. Acesso em: 03 nov. 2018.

1. **Wikipédia**, 2018. 
Disponível em: <<https://pt.wikipedia.org/wiki/Engenharia_de_Sistemas>>. Acesso em: 07 nov. 2018.

4. FRANCO, R. **Steps for requirements writing**, v. 10, n. 2, p.114, 2012. Disponível em: <<http://s3.amazonaws.com/host-article-assets/pmd/586fc52af7636eea018b4628/fulltext.pdf>>

5. COLE, A. **Qualidade Em Foco**, 2010. Disponível em: <<https://anielacole.wordpress.com/2010/09/28/modelo-em-v/>>. Acesso em: 07 nov. 2018.
   
6. MANTOVANI, M. **Quais são as vantagens e desvantagens do Modelo-V e quando usá-lo?** 2015. Disponível em:
   <<http://mariomantovani.blogspot.com/2015/06/quais-sao-as-vantagens-e-desvantagens.html>>. Acesso em: 07 nov. 2018.
   
7. **Tryqa**, 2013. What is V-model- advantages, disadvantages and when to use it? Disponível em: <<http://tryqa.com/what-is-v-model-advantages-disadvantages-and-when-to-use-it/>>. Acesso em: 03 nov. 2018.

8. **Guru99**, 2018. What is V Model? Learn with a Case Study using SDLC & STLC. 
Disponível em:<<https://www.guru99.com/software-testing-lifecycle.html)>> Acesso em: 07 nov. 2018.


