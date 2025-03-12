# Os fatores que influenciam os salários dos profissionais de dados no Brasil.

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

**Resumo**. Este projeto propõe o desenvolvimento de um sistema inteligente para analisar como fatores como nível de formação, experiência profissional, porte da empresa, região de residência e domínio de tecnologias específicas influenciam os salários dos profissionais de dados no Brasil. Utilizando técnicas de aprendizado de máquina e análise estatística, o sistema processará dados de diversas fontes para identificar padrões e correlações entre essas variáveis e a remuneração. O objetivo é fornecer insights precisos que auxiliem profissionais e empresas a entenderem melhor os fatores que impactam os salários no setor de dados, contribuindo para decisões estratégicas de carreira e gestão de talentos. 

---


## Introdução

O mercado de dados no Brasil está em constante expansão, e diversos fatores influenciam a remuneração dos profissionais da área. Aspectos como nível de formação, experiência profissional, porte da empresa, localização geográfica e domínio de determinadas tecnologias podem impactar significativamente os salários. Compreender essas variáveis é essencial tanto para profissionais que buscam crescimento na carreira quanto para empresas que desejam atrair e reter talentos. Neste contexto, este projeto propõe o desenvolvimento de um sistema inteligente capaz de analisar e identificar padrões salariais no setor de dados, auxiliando na tomada de decisões estratégicas.

###    Contextualização

Nos últimos anos, a área de ciência de dados tem se consolidado como um dos segmentos mais promissores do mercado de trabalho, impulsionada pelo crescimento da transformação digital e pelo uso intensivo de dados nas tomadas de decisão empresariais. Com essa expansão, há um aumento na demanda por profissionais qualificados, o que torna relevante a análise dos fatores que influenciam a remuneração desses especialistas.
Nesse contexto, este projeto se insere na interseção entre inteligência artificial, análise de dados e mercado de trabalho, buscando compreender como diferentes características dos profissionais de dados impactam seus salários no Brasil. Para isso, o estudo utiliza um sistema inteligente capaz de processar grandes volumes de informações e identificar padrões relacionados a variáveis como nível de formação, experiência profissional, porte da empresa, localização geográfica e domínio de tecnologias específicas. Essa abordagem possibilita uma análise mais precisa e baseada em evidências sobre os determinantes salariais no setor.

###    Problema

O problema central deste projeto é entender quais características dos profissionais de dados no Brasil afetam de forma mais significativa seus salários. Essa questão é relevante tanto para trabalhadores que buscam otimizar suas trajetórias profissionais quanto para empresas que desejam estabelecer políticas salariais mais competitivas. O contexto da aplicação envolve o mercado de tecnologia e ciência de dados, abrangendo profissionais de diferentes perfis, desde iniciantes até especialistas, que atuam em empresas de diversos portes e segmentos. O estudo se baseia em dados reais, extraídos de fontes como o State of Data - BR 2023, para analisar padrões e tendências salariais no setor. 

###    Objetivo geral

Desenvolver um sistema inteligente para analisar o impacto de fatores como nível de formação, experiência profissional, porte da empresa, localização geográfica e conhecimento em tecnologias nos salários dos profissionais de dados no Brasil, utilizando dados extraídos do State of Data - BR 2023 e outras fontes complementares. 

####    Objetivos específicos

Analisar a relação entre nível de formação, experiência profissional e porte da empresa com a remuneração dos profissionais de dados no Brasil, utilizando técnicas de aprendizado de máquina e análise estatística.

Investigar o impacto da localização geográfica e do domínio de determinadas tecnologias no salário dos profissionais, identificando possíveis desigualdades regionais e valorização de habilidades específicas no mercado.

Desenvolver modelos preditivos capazes de estimar faixas salariais com base nos atributos dos profissionais, fornecendo insights para tomada de decisão sobre carreira e políticas salariais.

Implementar visualizações interativas e relatórios analíticos para facilitar a interpretação dos padrões identificados, tornando os resultados acessíveis para diferentes perfis de usuários.


###    Justificativas

A crescente demanda por profissionais de ciência de dados no Brasil, aliada às variações salariais influenciadas por múltiplos fatores, torna essencial a compreensão dos elementos que impactam a remuneração desses especialistas. Segundo o artigo "Carreira em Dados: conheça as principais áreas e como ingressar" (Alura, 2023), aspectos como nível de formação, experiência, porte da empresa, localização geográfica e domínio de tecnologias exercem influência direta sobre as oportunidades e os ganhos no setor. No entanto, ainda há uma lacuna na identificação quantitativa e preditiva desses fatores, dificultando a tomada de decisão tanto para profissionais que buscam progressão na carreira quanto para empresas que desejam formular políticas salariais competitivas.
Diante desse cenário, este projeto se justifica pela necessidade de um sistema inteligente capaz de analisar e prever os impactos desses fatores nos salários dos profissionais de dados no Brasil. Ao utilizar dados extraídos do State of Data - BR 2023 e outras fontes complementares, o sistema busca gerar insights estratégicos baseados em evidências, permitindo um entendimento mais profundo da valorização profissional no setor. Além disso, a implementação de modelos preditivos e visualizações interativas possibilita a democratização da informação, fornecendo subsídios para que profissionais façam escolhas informadas sobre suas carreiras e empresas ajustem suas políticas de remuneração de forma mais eficiente e equitativa.



##    Público alvo

A aplicação será utilizada por diferentes perfis de usuários que buscam compreender os fatores que influenciam os salários no setor de ciência de dados no Brasil. Esses usuários podem ter níveis variados de conhecimento sobre tecnologia e estatística, mas todos compartilham o interesse em tomar decisões informadas com base em dados. A seguir, são descritos os principais perfis de usuários:

**Profissionais de Ciência de Dados e Tecnologia**
**Perfil:** Engenheiros de dados, cientistas de dados, analistas de dados e desenvolvedores que desejam entender melhor o impacto de fatores como experiência, formação acadêmica e habilidades tecnológicas em seus salários. 
**Conhecimento prévio:** Alto conhecimento técnico em programação, estatística e machine learning. Familiaridade com análise de dados e interpretação de gráficos interativos. 
**Relação com a tecnologia:** Usuários experientes, que podem usar os resultados do sistema para planejar sua progressão de carreira e negociar salários. 

**Profissionais em Transição de Carreira**
**Perfil:** Pessoas migrando para a área de dados, vindas de setores como engenharia, administração, marketing e finanças. 
**Conhecimento prévio:** Nível intermediário a básico em ciência de dados e estatística. Interesse em entender quais habilidades e qualificações são mais valorizadas no mercado. 
**Relação com a tecnologia:** Familiarizados com ferramentas básicas de análise de dados, mas podem necessitar de suporte na interpretação dos resultados. 

**Recrutadores e Gestores de RH**
**Perfil:** Profissionais de Recursos Humanos e gestores que contratam e definem políticas salariais para equipes de dados. 
**Conhecimento prévio:** Baixo conhecimento técnico sobre ciência de dados, mas familiaridade com tendências de mercado e estruturação de cargos e salários. 
**Relação com a tecnologia:** Usam a aplicação para comparar remunerações, identificar padrões e embasar decisões estratégicas de contratação. 

**Empresas e Tomadores de Decisão**
**Perfil:** Diretores e líderes de empresas de tecnologia e dados que desejam entender melhor a dinâmica salarial do setor para definir estratégias de retenção e contratação. 
**Conhecimento prévio:** Alto conhecimento sobre negócios e gestão, mas limitado em análise de dados e machine learning. 
**Relação com a tecnologia:** Buscam relatórios e insights claros para embasar decisões estratégicas. 

## Análise exploratórida dos dados

###    Dicionário de dados

**State of Data Brazil 2023**
A base de dados State of Data Brazil 2023 é rica em informações sobre profissionais no setor de dados no Brasil, abordando tanto características demográficas quanto aspectos profissionais e de experiência no mercado de trabalho.

Características Demográficas

Localização Geográfica

1. Estado onde Mora (P1_i)

Descrição: Estado onde o profissional reside atualmente.

Tipo de Dado: Categórico (nome do estado).



2. UF onde Mora (P1_i_1)

Descrição: Unidade Federativa (UF) onde o profissional reside atualmente.

Tipo de Dado: Categórico (sigla da UF).



3. Região onde Mora (P1_i_2)

Descrição: Região geográfica do Brasil onde o profissional reside (Norte, Nordeste, Sudeste, Sul, Centro-Oeste).

Tipo de Dado: Categórico (nome da região).




Características Demográficas

4. Idade (P1_a)

Descrição: Idade do profissional em anos.

Tipo de Dado: Numérico.



5. Faixa de Idade (P1_a_1)

Descrição: Faixa etária do profissional (por exemplo, 22-24, 30-34, etc.).

Tipo de Dado: Categórico.



6. Gênero (P1_b)

Descrição: Gênero do profissional (Masculino, Feminino, etc.).

Tipo de Dado: Categórico.



7. Etnia/Cor/Raça (P1_c)

Descrição: Etnia, cor ou raça do profissional.

Tipo de Dado: Categórico.



8. Nível de Ensino (P1_l)

Descrição: Nível de educação do profissional (Ensino Fundamental, Ensino Médio, Ensino Superior, Pós-Graduação).

Tipo de Dado: Categórico.




Aspectos Profissionais

9. Faixa Salarial Mensal (P2_a)

Descrição: Intervalo de renda mensal do profissional (por exemplo, R$2.000-R$4.000, R$8.000-R$12.000).

Tipo de Dado: Categórico.

Relevância: Permite comparar a renda com o custo de vida por estado.



10. Experiência Profissional em Dados (P2_d)

Descrição: Tempo de experiência do profissional na área de dados (menos de 1 ano, 1-2 anos, 3-5 anos, etc.).

Tipo de Dado: Categórico.

Relevância: Possibilita avaliar se a experiência influencia o salário em diferentes estados.



11. Cargo Atual (P2_e)

Descrição: Cargo ocupado pelo profissional (Analista de Dados, Cientista de Dados, Engenheiro de Dados, etc.).

Tipo de Dado: Categórico.

Relevância: Permite segmentar a análise salarial por cargo e verificar variações entre estados.



12. Tamanho da Empresa (P2_f)

Descrição: Porte da empresa onde o profissional trabalha (Startup, Pequena, Média, Grande Empresa, Multinacional).

Tipo de Dado: Categórico.

Relevância: Empresas maiores podem pagar salários diferentes dependendo da região.



13. Modelo de Trabalho (P2_j)

Descrição: Tipo de regime de trabalho (Presencial, Híbrido, Remoto).

Tipo de Dado: Categórico.

Relevância: Profissionais remotos podem ter maior flexibilidade para escolher estados com menor custo de vida.



14. Setor da Empresa (P2_h)

Descrição: Setor de atuação da empresa (Bancos, Tecnologia, Saúde, Varejo, etc.).

Tipo de Dado: Categórico.

Relevância: O setor pode impactar os salários pagos em diferentes estados.
      
**PIB Ótica renda UF**

A base Contas Regionais do Brasil, do IBGE, traz dados sobre o PIB, setores econômicos, participação estadual na economia, PIB per capita e população. 

1. Produto Interno Bruto (PIB)

   * Descrição: Valor monetário total de todos os bens e serviços finais produzidos dentro de uma unidade federativa em um período específico.
   * Tipo de dado: Numérico (em milhões de reais).
   * Frequência: Anual.

2. Participação Relativa no PIB Nacional

   * Descrição: Percentual que indica a contribuição de cada unidade federativa no PIB total do país.
   * Tipo de dado: Numérico (percentual).
   * Frequência: Anual.

3. PIB per Capita

   * Descrição: Média do PIB por habitante em cada unidade federativa.
   * Tipo de dado: Numérico (em reais).
   * Frequência: Anual.

4. Valor Adicionado Bruto (VAB) por Setor

   * Descrição: Contribuição de cada setor econômico ao PIB da unidade federativa.
   * Subcategorias:
        Agropecuária: Valor adicionado das atividades agrícolas e pecuárias.
        Indústria: Valor adicionado das atividades industriais, incluindo transformação, construção e extrativa mineral.
        Serviços: Valor adicionado das atividades de serviços, como comércio, transporte, comunicações e outros serviços.
   * Tipo de dado: Numérico (em milhões de reais).
   * Frequência: Anual.

5. Impostos sobre Produtos Líquidos de Subsídios

   * Descrição: Total de impostos cobrados sobre produtos, subtraídos os subsídios, contribuindo para o cálculo do PIB.
   * Tipo de dado: Numérico (em milhões de reais).
   * Frequência: Anual.

6. População Residente

   * Descrição: Número total de habitantes em cada unidade federativa.
   * Tipo de dado: Numérico (número de pessoas).
   * Frequência: Anual.

7. Unidade Federativa (UF)

   * Descrição: Nome da unidade federativa do Brasil.
   * Tipo de dado: Categórico (27 categorias correspondentes às 26 estados e ao Distrito Federal).

8. Região Geográfica

   * Descrição: Região do Brasil à qual a unidade federativa pertence.
   * Tipo de dado: Categórico (5 categorias: Norte, Nordeste, Sudeste, Sul, Centro-Oeste).
  
   Painel IDHM (UNDP Brasil)

1. Identificação e Localização Geográfica

Código do Município

Descrição: Código único (geralmente do IBGE) que identifica o município.

Tipo de Dado: Numérico/Categórico (identificador).


Município

Descrição: Nome do município.

Tipo de Dado: Categórico.


UF

Descrição: Sigla da Unidade Federativa em que o município está localizado.

Tipo de Dado: Categórico.


Região

Descrição: Região geográfica do Brasil (Norte, Nordeste, Sudeste, Sul, Centro-Oeste) em que o município se encontra.

Tipo de Dado: Categórico.


Ano de Cálculo/Referência

Descrição: Ano em que os dados foram coletados ou o índice foi calculado (por exemplo, 2010, 2015, etc.).

Tipo de Dado: Numérico/Categórico.



2. Indicadores Compostos do Desenvolvimento Humano

IDHM (Índice de Desenvolvimento Humano)

Descrição: Índice composto que sintetiza o desenvolvimento humano global do município, combinando os componentes de longevidade, educação e renda. O valor varia de 0 a 1, sendo que valores mais próximos de 1 indicam maior desenvolvimento.

Tipo de Dado: Numérico (Contínuo).


IDHM Vida Longa

Descrição: Componente do IDHM que reflete a dimensão da saúde e longevidade, geralmente mensurado por meio da expectativa de vida ao nascer.

Tipo de Dado: Numérico (Contínuo).


IDHM Educação

Descrição: Componente do IDHM relacionado à educação, levando em conta indicadores como a expectativa de anos de estudo e os anos médios de escolaridade dos adultos.

Tipo de Dado: Numérico (Contínuo).


IDHM Renda

Descrição: Componente do IDHM que avalia a dimensão econômica, normalmente calculado a partir do rendimento per capita.

Tipo de Dado: Numérico (Contínuo).



3. Indicadores Sociais e Econômicos

Expectativa de Vida ao Nascer

Descrição: Média de anos que uma criança, nascida naquele município, tem de expectativa de vida, refletindo condições de saúde e assistência médica.

Tipo de Dado: Numérico (Contínuo).


Anos Médios de Escolaridade

Descrição: Média dos anos de estudo da população adulta do município, indicando o nível educacional alcançado.

Tipo de Dado: Numérico (Contínuo).


Rendimento per Capita

Descrição: Média do rendimento per capita (geralmente em reais) no município, refletindo o poder aquisitivo médio dos moradores.

Tipo de Dado: Numérico (Contínuo).



4. Rankings e Comparações

Ranking do IDHM

Descrição: Posição do município em relação aos demais, com base no valor do IDHM. Esse ranking ajuda a identificar quais municípios estão à frente ou atrás no desenvolvimento humano.

Tipo de Dado: Numérico (Ordinal)Painel IDHM (UNDP Brasil)

1. Identificação e Localização Geográfica

Código do Município

Descrição: Código único (geralmente do IBGE) que identifica o município.

Tipo de Dado: Numérico/Categórico (identificador).


Município

Descrição: Nome do município.

Tipo de Dado: Categórico.


UF

Descrição: Sigla da Unidade Federativa em que o município está localizado.

Tipo de Dado: Categórico.


Região

Descrição: Região geográfica do Brasil (Norte, Nordeste, Sudeste, Sul, Centro-Oeste) em que o município se encontra.

Tipo de Dado: Categórico.


Ano de Cálculo/Referência

Descrição: Ano em que os dados foram coletados ou o índice foi calculado (por exemplo, 2010, 2015, etc.).

Tipo de Dado: Numérico/Categórico.



2. Indicadores Compostos do Desenvolvimento Humano

IDHM (Índice de Desenvolvimento Humano)

Descrição: Índice composto que sintetiza o desenvolvimento humano global do município, combinando os componentes de longevidade, educação e renda. O valor varia de 0 a 1, sendo que valores mais próximos de 1 indicam maior desenvolvimento.

Tipo de Dado: Numérico (Contínuo).


IDHM Vida Longa

Descrição: Componente do IDHM que reflete a dimensão da saúde e longevidade, geralmente mensurado por meio da expectativa de vida ao nascer.

Tipo de Dado: Numérico (Contínuo).


IDHM Educação

Descrição: Componente do IDHM relacionado à educação, levando em conta indicadores como a expectativa de anos de estudo e os anos médios de escolaridade dos adultos.

Tipo de Dado: Numérico (Contínuo).


IDHM Renda

Descrição: Componente do IDHM que avalia a dimensão econômica, normalmente calculado a partir do rendimento per capita.

Tipo de Dado: Numérico (Contínuo).



3. Indicadores Sociais e Econômicos

Expectativa de Vida ao Nascer

Descrição: Média de anos que uma criança, nascida naquele município, tem de expectativa de vida, refletindo condições de saúde e assistência médica.

Tipo de Dado: Numérico (Contínuo).


Anos Médios de Escolaridade

Descrição: Média dos anos de estudo da população adulta do município, indicando o nível educacional alcançado.

Tipo de Dado: Numérico (Contínuo).


Rendimento per Capita

Descrição: Média do rendimento per capita (geralmente em reais) no município, refletindo o poder aquisitivo médio dos moradores.

Tipo de Dado: Numérico (Contínuo).



4. Rankings e Comparações

Ranking do IDHM

Descrição: Posição do município em relação aos demais, com base no valor do IDHM. Esse ranking ajuda a identificar quais municípios estão à frente ou atrás no desenvolvimento humano.

Tipo de Dado: Numérico (Ordinal)

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




