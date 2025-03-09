# TITULO DO PROJETO

INTEGRANTES:

Antonio Augusto Vieira Lopes Filho, aavlfilho@sga.pucminas.br

Diego Rodrigo Marinho Silva, diego.marinho@sga.pucminas.br

Rodrigo Ossen Ali Rodrigues, roarodrigues@sga.pucminas.br

Ryan Junio de Oliveira, ryan.junio@sga.pucminas.br

Vinicius Bigonha Cancela Moraes de Melo Filho, vbcmmfilho@sga.pucminas.br  

---

Professor:

Prof. Hugo Bastos de Paula
---

_Curso de Ciência de Dados, Unidade Praça da Liberdade_

_Instituto de Informática e Ciências Exatas – Pontifícia Universidade de Minas Gerais (PUC MINAS), Belo Horizonte – MG – Brasil_

---

**Resumo**. Este trabalho busca investigar a relação entre a qualidade da educação básica em diferentes estados brasileiros e as oportunidades profissionais no mercado de dados. Com base em dados da pesquisaState of Data BR 2023 e indicadores educacionais do INEP, o estudo analisará se profissionais formados em estados com melhores índices educacionais (como IDEB e investimento por aluno) alcançam cargos mais altos e apresentam faixas salariais superiores. A pesquisa pretende fornecer insights sobre como desigualdades educacionais podem impactar a trajetória profissional e a distribuição de talentos no setor de dados.

---


## Introdução

O mercado de dados no Brasil cresce exponencialmente, impulsionado pela transformação digital e a crescente adoção de tecnologias analíticas. No entanto, é notório que o acesso a esse mercado, especialmente para cargos de maior prestígio e remuneração, pode estar associado a fatores socioeconômicos e educacionais. A qualidade da educação básica, medida por indicadores como o IDEB, influencia diretamente as habilidades técnicas e socioemocionais adquiridas, afetando o desempenho acadêmico posterior e, consequentemente, as oportunidades de carreira. Diante desse cenário, este estudo busca investigar se profissionais de estados com melhores indicadores educacionais apresentam trajetórias de carreira mais bem-sucedidas em termos de cargo e salário. 

###    Contextualização

Na **contextualização**, o aluno deve dizer do que se trata o trabalho, em que área ou contexto se insere. 
A **contextualização** deve ser desenvolvida de algo mais genérico para algo mais específico. 
A citação de pesquisas quantitativas é bem aceita aqui (corretamente referenciadas).

###    Problema

Nesse momento você deve apresentar o problema que seu agente pretende resolver. 
No entanto, não é a hora de comentar sobre a aplicação.
Descreva também o contexto em que essa aplicação será usada, se  houver: 
empresa, tecnologias, etc. Novamente, descreva apenas o que de  fato existir, 
pois ainda não é a hora de apresentar requisitos  detalhados ou projetos.

O **problema** pode ser algo vivido em uma empresa específica. Neste caso, o aluno deve 
sucintamente apresentar o cenário de problema da empresa. A empresa só deve ser citada 
explicitamente se o aluno tiver autorização para tal.

> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)


###    Objetivo geral

Desenvolver um sistema inteligente para analisar se profissionais formados em estados brasileiros com melhores indicadores educacionais (IDEB, investimento por aluno, escolaridade média) alcançam cargos de maior senioridade e apresentam salários superiores no mercado de dados.

####    Objetivos específicos

1. Analisar a Relação entre Educação e Sucesso Profissional: Identificar se há uma correlação significativa entre os indicadores educacionais dos estados e os salários ou cargos ocupados pelos profissionais.
 2. Comparar Dados de Diferentes Estados: Coletar e comparar dados de salários e cargos de profissionais formados em estados com diferentes níveis de indicadores educacionais.
3. Identificar Fatores Contribuintes: Investigar outros fatores que podem influenciar o sucesso profissional, como rede de contatos, experiência prévia e setor de atuação.
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)


###    Justificativas

A educação é um dos principais determinantes do sucesso profissional. Estados com melhores indicadores educacionais tendem a oferecer uma formação mais robusta, o que pode resultar em profissionais mais capacitados e preparados para o mercado de trabalho. Compreender essa relação pode ajudar a direcionar políticas públicas e investimentos em educação, além de auxiliar indivíduos em suas escolhas acadêmicas e profissionais. Além disso, essa análise pode revelar desigualdades regionais que precisam ser abordadas para promover uma sociedade mais equitativa.
> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)



##    Público alvo

Estudantes e Recém-Formados: Para que possam tomar decisões informadas sobre onde estudar e quais áreas seguir.
 
 Instituições de Ensino: Para que possam entender a importância de melhorar seus currículos e infraestrutura.
 
 Empregadores e Recrutadores: Para que possam considerar a origem educacional dos candidatos em seus processos de seleção.

Políticos e Formuladores de Políticas Públicas: Para que possam desenvolver estratégias que melhorem a educação em estados com indicadores mais baixos.


> **Links Úteis**:
> - [Público-alvo](https://blog.hotmart.com/pt-br/publico-alvo/)
> - [Como definir o público alvo](https://exame.com/pme/5-dicas-essenciais-para-definir-o-publico-alvo-do-seu-negocio/)
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)


## Análise exploratórida dos dados

###    Dicionário de dados

Apresente uma descrição das bases de dados a serem utilizadas. 
Dicionários de dados devem conter as bases de dados, os nomes dos atributos 
com seu significado, seu tipo (inteiro, real, textual, categórico, etc).

Este projeto deve utilizar pelo menos duas fontes de dados. Uma fonte principal e 
uma fonte para enriquecimentos dos dados principais.


###    Descrição de dados

Utilize a análise descritiva baseada em estatística de primeira ordem para descrever os dados.
Como descrever dados numéricos: média, desvio padrão, mínimo, máximo, quartis, histograma, etc.
Como descrever dados qualitativos (categóricos): moda (valor mais frequente), quantidade de valores distintos (categorias), distribuição das categorias (histograma), etc.


## Preparação dos dados

A preparação dos dados consiste dos seguintes passos:

> - Seleção dos atributos
> - Tratamentos dos valores faltantes ou omissos: remoção, substituição, indução, etc.
> - Tratamento dos valores inconsistentes: conversão, remoção de dados duplicados, remoção ou tratamento de ouliers.
> - Conversão de dados: p. ex. numérico para categórico, categórico para binário, etc.


## Indução de modelos

### Modelo 1: Algoritmo

Substitua o título pelo nome do algoritmo que será utilizado. P. ex. árvore de decisão, rede neural, SVM, etc.
Justifique a escolha do modelo.
Apresente o processo utilizado para amostragem de dados (particionamento, cross-validation).
Descreva os parâmetros utilizados. 
Apresente trechos do código utilizado comentados. Se utilizou alguma ferramenta gráfica, apresente imagens
com o fluxo de processamento.

### Modelo 2: Algoritmo

Repita os passos anteriores para o segundo modelo.


## Resultados

### Resultados obtidos com o modelo 1.

Apresente aqui os resultados obtidos com a indução do modelo 1. 
Apresente uma matriz de confusão quando pertinente. Apresente as medidas de performance
apropriadas para o seu problema. 
Por exemplo, no caso de classificação: precisão, revocação, F-measure, acurácia.

### Interpretação do modelo 1

Apresente os parâmetros do modelo obtido. Tentre mostrar as regras que são utilizadas no
processo de 'raciocínio' (*reasoning*) do sistema inteligente. Utilize medidas como 
o *feature importances* para tentar entender quais atributos o modelo se baseia no
processo de tomada de decisão.


### Resultados obtidos com o modelo 2.

Repita o passo anterior com os resultados do modelo 2.

### Interpretação do modelo 2

Repita o passo anterior com os parâmetros do modelo 2.


## Análise comparativa dos modelos

Discuta sobre as forças e fragilidades de cada modelo. Exemplifique casos em que um
modelo se sairia melhor que o outro. Nesta seção é possível utilizar a sua imaginação
e extrapolar um pouco o que os dados sugerem.


### Distribuição do modelo (opcional)

Tende criar um pacote de distribuição para o modelo construído, para ser aplicado 
em um sistema inteligente.


## 8. Conclusão

Apresente aqui a conclusão do seu trabalho. Discussão dos resultados obtidos no trabalho, 
onde se verifica as observações pessoais de cada aluno.

Uma conclusão deve ter 3 partes:

   * Breve resumo do que foi desenvolvido
	 * Apresenação geral dos resultados obtidos com discussão das vantagens e desvantagens do sistema inteligente
	 * Limitações e possibilidades de melhoria


# REFERÊNCIAS

Como um projeto de sistema inteligente não requer revisão bibliográfica, 
a inclusão das referências não é obrigatória. No entanto, caso você 
tenha utilizado referências na introdução ou deseje 
incluir referências relacionadas às tecnologias, padrões, ou metodologias 
que serão usadas no seu trabalho, relacione-as de acordo com a ABNT.

Verifique no link abaixo como devem ser as referências no padrão ABNT:

http://www.pucminas.br/imagedb/documento/DOC\_DSC\_NOME\_ARQUI20160217102425.pdf

Por exemplo:

**[1]** - _ELMASRI, Ramez; NAVATHE, Sham. **Sistemas de banco de dados**. 7. ed. São Paulo: Pearson, c2019. E-book. ISBN 9788543025001._

**[2]** - _COPPIN, Ben. **Inteligência artificial**. Rio de Janeiro, RJ: LTC, c2010. E-book. ISBN 978-85-216-2936-8._

**[3]** - _CORMEN, Thomas H. et al. **Algoritmos: teoria e prática**. Rio de Janeiro, RJ: Elsevier, Campus, c2012. xvi, 926 p. ISBN 9788535236996._

**[4]** - _SUTHERLAND, Jeffrey Victor. **Scrum: a arte de fazer o dobro do trabalho na metade do tempo**. 2. ed. rev. São Paulo, SP: Leya, 2016. 236, [4] p. ISBN 9788544104514._

**[5]** - _RUSSELL, Stuart J.; NORVIG, Peter. **Inteligência artificial**. Rio de Janeiro: Elsevier, c2013. xxi, 988 p. ISBN 9788535237016._



# APÊNDICES

**Colocar link:**

Do código (armazenado no repositório);

Dos artefatos (armazenado do repositório);

Da apresentação final (armazenado no repositório);

Do vídeo de apresentação (armazenado no repositório).




