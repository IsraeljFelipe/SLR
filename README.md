# SLR
Systematic Literature Review (SLR) - tips and procedures

Por Mariane Nóbrega, Ph.D. student
Supervisão: prof. Israel José dos Santos Felipe, Ph.D.

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
Este documento pretende fornecer um panorama geral sobre a realização de uma revisão sistemática da literatura (systematic literature review – SLR) nas ciências sociais aplicadas, especificamente nas áreas de administração de empresas e ciências contábeis. Uma SLR deve gerar um framework na área de interesse, respondendo a uma ou mais questões de pesquisa e sendo replicável, por isso, normalmente, segue-se protocolos para sua execução.

O primeiro passo para iniciar uma SLR é pesquisar outras SLR já existentes sobre o tema. Isso vai servir para identificar a relevância da sua SLR e para indicar um caminho a ser seguido, o que estará na justificativa do seu trabalho. Você pode começar pelo próprio Google Acadêmico e depois pesquisar no Periódicos Capes.

O processo de seleção dos documentos científicos relevantes em uma SLR envolve gerenciar um conjunto de dados grande e, muitas vezes, não muito organizado. A cada vez que se amplia o escopo ou a estratégia de busca, pode-se gerar ainda mais resultados irrelevantes para o foco da sua SLR.

Assim, cada vez mais se intensifica o uso de técnicas de machine learning e text mining para automação do processo de revisões sistemáticas em diversas ferramentas propostas. Pode-se citar ferramentas aplicadas para área de ciências médicas, compatíveis apenas como as bases de dados dessa área (PUBMED, MEDLINE ou O´Mara-Eves dataset): RobotReviewer, LINGO3G, GATE, Abstrackr, Twister, SparkText e SwiftReview. Outras ferramentas incluem: libsvm (Library for Support Vector Machines), scikit-learn, Weka. Muitas dessas ferramentas utilizam técnicas como a tokenização de palavras e sentenças.

Nesse sentido, entende-se que há uma grande relevância na construção da estratégia de busca, que, quando é falha, gera resultados errados ou imprecisos. Para mitigar essas falhas é interessante elaborar corretamente a pergunta/questão de pesquisa, que, quando bem estruturada, refletirá em uma estratégia de busca adequada.

Várias estratégias são utilizadas para construção da questão de pesquisa, como as estratégias PICO, PICOC, PICo, 3WH, BeHEMoTh, CIMO, PEO, PEICO(S), PICOT, PICOTS, PICOTT, PVO, PICOD, SPICE, SPIDER, PCC, ECLIPSE e TQO. A grande maioria é voltada para a área da saúde, mas algumas podem ser adaptadas para outras áreas.

Um dos mais famosos é o modelo PICO, de Richardson, Wilson, Nishikawa e Hayward (1995), que considera:

P - população, paciente/indivíduos ou problema abordado (Population/Patient/Problem);
I - intervenção ou a exposição que será considerada (Intervention);
C - comparação da intervenção ou da ação quando esta for necessária e relevante (Comparison/Control); Nem sempre esse item é contemplado; e
O - desfechos ou resultados esperados de interesse (Outcome).
Exemplo de construção:

Questão de pesquisa: Como as métricas mais utilizadas para sustentabilidade organizacional diferem das métricas de desempenho tradicionais?
Termos para PICO: sustentabilidade (P), métricas para sustentabilidade (I), métricas tradicionais (C), desempenho organizacional (O);
Tradução para busca: sustainability (P), metrics for sustainability (I), traditional metrics (C), organizational performance (O);
Combinações/strings de busca específicas: ESG OR “environmental, social and governance” OR “corporate social responsibility” OR CSR (P); metrics OR score OR ranking OR indicators (I), “performance measures” (C), organizational AND (actuation OR action OR behavior OR conduct) (O);
Construção da estratégia de busca: ((ESG OR “environmental, social and governance” OR “corporate social responsibility” OR CSR) AND (metrics OR score OR ranking OR indicators) AND “performance measures” AND organizational AND (actuation OR action OR behavior OR conduct));
Normalmente as variações do modelo PICO mantem esses tópicos principais e incluem alguns outros tópicos que podem ajudar a busca. Um exemplo interessante é a estratégia PICOC (Population, Intervention, Comparison, Outcome, Context), que inclui o contexto da pesquisa, como localização geográfica. A PICOC é a estratégia utilizada pela ferramenta Parsifal, software online para construção de SLRs.

Outra estratégia interessante é a PICOD ou PICOS, que considera o design (desenho) do estudo ou study design (desenho do estudo). Essa estratégia inclui a busca pelos instrumentos de coletas de dados ou métodos de pesquisa utilizados nos estudos, por exemplo regressão (regression) ou painel (panel data). Nesse caso, a experiência do pesquisador pode ser útil para restringir os métodos considerados mais adequados no tipo de estudo em questão.

Também é importante destacar que se trata de um processo de tentativa e erro até se encontrar a estratégia de busca mais adequada em cada base de dados. O uso de descritores, operadores booleanos (and, or, not e same) e caracteres coringas (como os truncadores *, ? ou $) podem ajudar, mas a transformação do objetivo/problema de pesquisa na estratégia de busca é mais conceitual. Novamente, a experiência de leitura do pesquisador o ajudará a selecionar o vocabulário controlado (as padronizações) específico da área em que pesquisa, para que se coloque descritores e sinônimos, além das possibilidades de plural/singular e grafias. Para o plural, é possível truncar o final de uma palavra, por exemplo, ao invés de utilizar “metric for sustainability OR metrics for sustainability” é possível utilizar apenas “metric$ for sustainability”. Pode-se utilizar uma interrogação (?) para substituir apenas um caractere, por exemplo ?SG para ESG (que também pode ser encontrado na sigla em português “ASG”), utilizar um asterisco (*) para substituir um ou mais caracteres, como responsib* para as variações de responsibility, e um cifrão ($) para substituir um ou nenhum caractere, como em metric$, que retornará singular (metric) ou plural (metrics).

Além disso, é necessário definir filtros para os critérios de inclusão/exclusão da busca estipulados pelo pesquisador, como recorte temporal, disponibilidade de acesso (ex.: texto completo disponível), área de publicação, autor(es) de referência, cobertura, idioma e número de páginas. Devem ser informados os motivos de inclusão/exclusão. Lembrando que, a depender das bases de dados escolhidas para as buscas, será necessário mesclar os resultados ao final para remover arquivos duplicados.

Além dessa construção da string de busca, cabe ao pesquisador escolher os tipos de documentos que serão considerados (cobertura). A comunidade acadêmica, de forma geral, opta por referências tradicionais, advindas de, normalmente, arquivos digitais de revistas científicas digitais (periódicos/journals), que passam por critérios de aceitação, como peer-review, blind- review ou escolha pelos editores ou conselho/comissão editorial, sendo consideradas white papers.

Todavia, referências não convencionais, como open-archives (e-prints), pre-prints e open-access, têm sido consideradas importantes em casos de temas incipientes ou com poucos estudos disponíveis. Trata-se da chamada grey literature, que envolve, ainda, proceedings de eventos científicos/acadêmicos (normalmente anais de congressos/conferências), livros/livros indexados, teses e dissertações (há bancos de teses e dissertações disponíveis por várias instituições de ensino) e documentos variados. Assim, é possível que várias formas de difusão do conhecimento científico sejam utilizadas como fontes de informação. A grey literature normalmente não está publicada em canais convencionais de transmissão científica e sua qualidade mínima não foi garantida por pareceristas.

Os repositórios do tipo open access (repositórios de Arquivos de Acesso Livre, como repositórios institucionais) podem incluir documentos com probabilidade de se transformar em white papers (assim como os opens archives), ampliando a possibilidade de se publicar pesquisas em desenvolvimento e abertos a sugestões de melhorias e críticas. Assim, trabalhos em andamento em forma de pre-prints são publicados em open-archives para passar pelo crivo da comunidade científica. Os open archives são disponibilizados em repositórios como o Portal de Periódicos da Capes, porém são vinculados a instituições, como cursos de pós-graduação de universidades. É o caso dos working papers da Faculdade de Economia, Administração, Contabilidade e Atuária (FEA-USP).

Porém, é importante destacar que, sobretudo na área de ciências sociais aplicadas, se espera que essa “transformação” ocorra em um intervalo de tempo menor do que em outras áreas (como na área das ciências médicas). Entende-se que a publicação em revistas científicas pode requerer um tempo considerável, podendo chegar até a um ano (revistas que demoram mais que isso normalmente são de baixa qualidade). Nesse sentido, deve-se prestar atenção à versões eletrônica, pois um documento científico qualquer que passe mais de cinco anos sem ser publicado em periódicos têm sua probabilidade de publicação reduzida, e, portanto, seu uso deve ser repensado.

Além disso, existem pontuações de open access, gerando duas formas principais: o gold open access (gold OA), cujos periódicos normalmente estão disponíveis no Diretório de Jornais de Acesso Aberto (Directory of Open Access Journals - DOAJ), e o green open acess (green OA ou self-archiving/autoarquivamento), cuja versão do manuscrito fica totalmente acessível em um repositório. Um gold OA tem sua versão final acessível permanentemente sem restrições após a publicação e os direitos autorais pertencem aos autores (os autores devem ser citados em caso de utilização do trabalho por outras pessoas). Já no caso dos green OA, a versão depositada em um repositório depende do financiador, pois os direitos autorais são da editora do periódico, havendo restrições para utilização do trabalho por outros pesquisadores, a depender das políticas de self-archiving.

Outro ponto importante a se destacar sobre uma SLR é a recomendação de que ela seja realizada por mais de uma pessoa, de preferência uma equipe. Muitas vezes isso é difícil, mas é interessante se tentar fazer com pelo menos duas pessoas, para melhorar a credibilidade dos resultados.

De forma geral, percebe-se que o processo de SLR inclui o planejamento, o desenvolvimento e os resultados. O planejamento envolve:

uma pesquisa exploratória para avaliar a necessidade da SLR (se já existem SLRs sobre o tema e qual a justificativa para uma nova);
a escolha de um protocolo (como um PRISMA ou outro específico da área), com o intuito de reduzir a possibilidade de vieses;
a definição de pelo menos uma questão de pesquisa e do objetivo e escolha dos seus termos/descritores;
a escolha da estratégia de busca com base em um modelo, como o PICO, o PICOC ou o PICOD;
a definição de possibilidades de sinônimos ou variações para esses termos (dentro do vocabulário padrão ou predominante na área de interesse);
a escolha dos repositórios ou bases de dados a serem utilizadas, como WoS e Scopus;
a construção da string de busca com auxílio de operadores booleanos e caracteres curinga;
a escolha dos critérios de seleção/inclusão e dos critérios de exclusão;
testes nas bases de dados para a escolha da string mais adequada. É importante dizer que normalmente há várias mudanças no argumento original de busca, inclusive podendo haver mudanças de base para base.
a escolha dos critérios de qualidade a serem considerados, por exemplo, relacionados ao que se espera encontrar nos objetivos, metodologia ou resultados dos trabalhos analisados (Ex.: A questão de pesquisa foi respondida?). Inclusive é interessante estipular uma “classificação” para os estudos (por exemplo, uma nota de 0 a 5, a depender dos critérios estipulados).
A partir desse planejamento, o desenvolvimento propriamente dito da SLR envolve seguir as etapas definidas pelo protocolo escolhido, extrair os arquivos ou os metadados dos documentos retornados em cada base de dados e selecionar os estudos que farão parte da SLR. O pesquisador pode extrair os arquivos completos em .pdf ou apenas seus metadados, no formato BibTeX.

O processo de seleção pode iniciar com a leitura (screening) dos títulos, resumos e palavras-chave, que possivelmente acarretará a exclusão de alguns trabalhos. Em seguida, pode-se optar por ler a introdução e a conclusão e, por fim, o texto inteiro, sempre registrando todos os trabalhos que foram incluídos ou excluídos (conforme os critérios de qualidade estabelecidos), de preferência em um documento, como o PRISMA Flow Diagram. Ao final é importante analisar se os estudos remanescentes têm as informações necessárias para responder à questão de pesquisa. Por isso, muitas vezes é interessante que o estudo não seja feito por apenas um pesquisador, pois a avaliação dos estudos selecionados, a imparcialidade e a objetividade são de suma importância. Além disso, a revisão dos estudos selecionados deve garantir que trabalhos relevantes não tenham sido excluídos do pool. Nesta etapa, podem ser utilizados formulários de extração de dados, detalhando informações necessárias para responder à questão de pesquisa.

Esse processo de seleção pode ser bastante demorado e intenso, a depender do cronograma estabelecido. Assim, pode ser útil utilizar alguma ferramenta/software específico para SLRs, como o Parsifal, o StArt e o SLR Tool, que serão detalhados nos tópicos X. Também podem ser utilizadas planilhas do Excel, a depender do nível de organização do pesquisador (o processo de seleção manual pode levar a resultados com baixa confiabilidade).

Por fim, os resultados devem ser relatados a partir de um artigo científico ou mesmo como parte de uma dissertação ou tese. Podem ser utilizados métodos estatísticos, tabelas, gráficos, figuras, etc. Nesta etapa também podem ser utilizados alguns softwares, como, por exemplo, gerenciadores de referências, como Mendeley, Zotero, EndNote ou JabRef, que também ajudam no gerenciamento dos metadados dos documentos e na checagem final das referências.
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
