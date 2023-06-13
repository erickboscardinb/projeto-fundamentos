<img src='/img/logo.png' alt='logo da empresa' width='150px' heidth='150px'/>

# *Coach Sports*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Pedro Henrique Baltazar da Silva|Desenvolvedor|pedro.baltazar@estudante.ifro.edu.br|
|Thauan Wictor Alves Muniz|Desenvolvedor|thauanwictor05@gmail.com|
|Erick Brayan Boscardim Barbosa|gerente do projeto|erickbosca@gmail.com|
|Natam Menegheti Farias|desenvolvedor|natammfarias@gmail.com|
|Alisson Dias da Silva| Desenvolvedor| diasdasilvaalisson75@gmail.com|
|Lemuel Berequias Santana Lemes De Souza|Desenvolvedor| santanalemue@gmail.com|
 
# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Coach Sports|
| GERENTE DO PROJETO | Erick Brayan Boscardim Barbosa |
| PRINCIPAL OBJETIVO | A empresa Coach Sport 's trata-se de uma empresa focada em artigos de esportes em geral, vendemos camisas, bolas, tenis esportivos, redes profissionais, etc... Nosso objetivo é ser ou estar entre uma das melhores lojas de vendas nesse ramo, prezando a qualidade e satisfação do cliente sempre. Atualmente estamos há 5 anos no mercado de trabalho e com uma ótima clientela. |
| BENEFÍCIOS ESPERADOS |* Melhor Loja de vilhena em artigos esportivos;<br/>* Preços especiais ;<br/>* Qualidade garantida;<br/>* Frete gratis para todo o Brasil;<br/>  | 04/04/2023 - 07/12/2023 |

[ [INÍCIO](#fibonacci-management-system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, atletas, amantes de demais esportes, escolas, e centros de treinamento e demais interessados neste projeto. O objetivo deste documento é apresentar uma descrição dos serviços e funções que o sistema **Coach Sports** deve provar, bem como suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e textículos. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as deficiências identificadas durante a fase de concepção do sistema.
Concepção do sistema:
Foram necessários apenas alguns amigos com um sonho empreendedor de ter uma loja de esportes:

## CONCEPÇÃO DO SISTEMA

Foram necessarios apenas alguns amigos com um sonho empreendedor de terem uma loja de esportes :
* Pedro Baltazar foi o responsavel pela entrevista:
  * Discussões individuais de um representante da equipe com Erick Brayan, diretor da loja Coach Sports.
* Consulta com especialista:
  * Alisson,Treinador do Clube de Regatas do Flamengo, orientou na concepção da empresa devido sua experiência em trabalhar com times e esportes e ser um dos consultores da empresa;
  * Thauan Wictor, professor de Educação fisica da Universidade Federal, orientou na análise de requisitos devido a sua grande experiência em Interações com pessoas;
  * Natam, Personal Trainer, foi outro entrevistado;
  * Lemuel, responsável pelo treinamento dos Atletas Olimpicos da seleção do BRASIL.
* Prototipação:
  * Representações dos esportes com diferentes níveis de fidelidade, a melhor em qualidade e com autenticidade de ponta.



## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* EaD: Esportes a Distância.
* SolCS: Site oficial das lojas Coach Sports.
* Esporte inclusivo: Destinada a pessoas com deficiências de locomoção e intelectual.
[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O projeto consiste nas v
endas de produtos esportivos e vestimentas apropriadas para o esporte, que possa atender aos amantes de cada esporte existente. O projeto visa auxiliar o sistema de ensino esportivos através de doações de materiais esportivos que serão usadas por funcionários e alunos da instituição de ensino. O escopo do produto pode ser consultado nos requisitos do software.
O escopo do **Arsenal esportivo** pode ser consultado nos [requisitos do software](#requisitos-do-software)

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Vendas de materiais de baixa qualidade;
* Vendas de materiais falsificados ou estragados;
* Testes de materiais dentro das lojas;

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à instituição e pela alocação de outros administradores|
|**Coordenador:**|Responsáveis pela aprovação de disciplinas, turmas e matrículas realizadas pela secretaria do curso, além de ser responsável pela alocação da secretaria|
|**Secretaria:**|Responsáveis pelo cadastramento de disciplinas e turmas, pela alocação de professores e monitores de um curso e matrículas dos alunos|
|**Professor:**|Responsáveis pela criação do programa da disciplina através de ferramentas de planejamento e criação de atividades|
|**Aluno:**|Seguem o programa da disciplina criada pelo professor, tendo como apoio ferramentas de comunicação, tal como: chat e fórum|

## Abrangência e sistemas similares

### Abrangência:

O sistema irá conter ferramentas para construção de um plano de aulas que esteja de acordo com os objetivos e metodologia de uma turma ministrada pelo professor. O professor através de ferramentas (como Chat, Fórum, Base de Documentos) irá montar o programa desta disciplina que deverá ser seguido pelo aluno usuário do sistema. O professor terá a liberdade de criar atividades (textos e questionários) e determinar prazos a serem cumpridos pelos alunos. Serão armazenadas as resoluções dos alunos para serem corrigidas pelo professor posteriormente, gerando estatísticas do desempenho de cada aluno e da turma. O sistema também irá prover o gerenciamento das entidades que compõem a instituição e os usuários do sistema.

Dentre as ferramentas de comunicação do sistema existirão as assíncronas, como Chat, onde poderão ser feitas reuniões, discussões, explicações conjuntas ou qualquer outra atividade de comunicação. O Fórum consiste na ferramenta síncrona usada para os mesmos fins do Chat.

Das ferramentas de planejamento podemos citar:

* **Avaliações e Exercícios:** serão criadas tarefas a serem entregues pelos alunos nos determinados prazos;

* **Anúncios:** espaço para criação de avisos e informes aos alunos de uma determinada turma;

* **Manipulação de Arquivos:** haverá um diretório onde podem ser acumulados arquivos de diversos tipos pelos usuários;

* **Planejamento de Aulas:** planejamento de uma aula estruturada com leituras e exercícios.

### Sistemas similares:

No cenário atual da universidade se encontra um sistema que é responsável por realizar tal tarefa, denominado Virtus, porém o sistema não atende todas as necessidades, não sendo considerado satisfatório pela maioria dos usuários.

No cenário nacional encontram-se três sistemas que se destacam:

**AulaNet:** é um ambiente de software baseado na Web, desenvolvido no Laboratório de Engenharia de Software - LES - do Departamento de Informática da PUC-Rio, para administração, criação, manutenção e participação em cursos à distância.
WebAula: é um produto formado por soluções integradas de gerenciamento de aprendizagem, conhecimento e conteúdos on-line, resultado de uma joint venture entre as empresas Zargon e Poliedro.

**TelEduc:** é um ambiente para a criação, participação e administração de cursos na Web. Ele foi concebido tendo como alvo o processo de formação de professores para informática educativa, baseado na metodologia de formação contextualizada desenvolvida por pesquisadores do Nied (Núcleo de Informática Aplicada à Educação) da Unicamp.

No cenário internacional os sistemas de maior porte são:

**WebCT:** O WebCT é um programa que possibilita a criação de ambientes educacionais na Internet, desenvolvido pela University of British Columbia - Canadá. Ele permite a colocação do conteúdo de um curso na Internet pelo professor e, em seguida, o cadastro os alunos que participarão daquele curso. O objetivo principal é possibilitar a interação entre tais sujeitos através de ferramentas de trabalho em grupo, tais como: fóruns de discussão, chat, palestras on-line, além de facilitar a comunicação professor-aluno, através da publicação de notas e gabaritos de avaliações.

**Blackboard:** é um sistema de autoria extremamente amigável, desenvolvido para ser utilizado por educadores e profissionais interessados em aplicar as novas tecnologias interativas da rede na educação, contribuindo para a metodologia de ensino presencial e potencializando o processo de ensino e aprendizagem a distância.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um computador com a seguinte configuração mínima:

* Processador Dual Core 2GHz ou superior
* 2Gb de memória RAM
* 5Gb de armazenamento em disco
* Para uso do sistema é preciso ter instalado o Java SE versão 8 e o MySql versão 8.0.28.

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Os colaboradores da empresa contratante possuem bastante experiência com aplicações desta natureza, os analistas também estão familiarizados com esta área de aplicação comercial, porém o sistema utiliza uma tecnologia nova, com a qual os analistas e programadores não estão familiarizados. No que se refere ao tamanho do sistema, trata-se de um projeto de médio porte, com baixo nível de complexidade, que não será integrado a outros sistemas, limitando-se a atender a demanda da escola no que se refere à EaD, que, atualmente possui 1.000 alunos matriculados. Conclui-se que o projeto possui viabilidade técnica, em virtude dos baixos riscos identificados.

## Viabilidade Econômica

Foi realizada uma análise de custo-benefício, e, mesmo com estimativas conservadoras do retorno sobre o investimento e dos benefícios totais, este projeto é viável economicamente. Após a implantação, espera-se uma melhoria na qualidade dos serviços prestados e aumento da capacidade de vagas da unidade escolar.

## Viabilidade Organizacional

Do ponto de vista organizacional, este projeto apresenta baixo risco. Os diretores e coordenadores da instituição demonstram forte interesse no projeto. Espera-se que os professores e alunos aprovem a implantação do sistema, visto que atualmente a escola não possui uma ferramenta específica para o controle das informações, o que está provocando enormes transtornos para a instituição.


[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento


[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RF-001 |Compras | Um programa que conta a quantidade de compras que o cliente fez. |
|RF-002 |Cadastro |O sistema deverá fazer cadastros de novos clientes. |
|RF-003 |Controle de estoque| Um programa que sabe a quantidade de produtos no estoque.|
|RF-004 |Controle de estoque|Um programa que realiza o aluguel de artigos esportivos|
|RF-005 |Método de pagamento|Fazer com que o sistema tenha diversas formas de pagamento sejam utilizadas como
pic pay, cartão de crédito, debito, dinheiro etc.|
|RF-006|Prestações|Fazer com que o sistema conta com prestações para que o cliente tenha a
possibilidade de pagar a prestação.|
|RF-007 |Carrinho para as compras|Ter um sistema que conta com a possibilidade de adicionar carrinhos caso o usuário
goste do produto e queira comprar mais tarde.|
|RF-008 |Notificações de ofertas|Ter um sistema que realiza notificação quando há alguma oferta do produto que ele
deseje.|
|RF-009 |Chegada de produtos no estoque|Realizar um programa de banco que armazena cada produto que chegar no estabelecimento.|
|RF-010 |saida do estoque|Realizar um programa que contabiliza cada produto que sai da loja|
|RF-011 |Possibilitar vendas|O sistema deve possibilitar as vendas de produtos esportivos para todas as idades.|
|RF-012 |Doação |O sistema deve possibilitar a doação de produtos esportivos que serão usados pelos professores juntos com seus alunos.|
|RF-013 |Controle de qualidade |O sistema deve possibilitar a revisão dos produtos, e a divisão dos de baixa qualidade com os de alta qualidade.|
|RF-014 |chat|O sistema deve ter um meio de comunicação entre o vendedor e o cliente.|
|RF-015 |Ajuda para deficientes|Ter um botão de fácil acesso caso o cliente/usuário que tenha alguma deficiência física. .|
|RF-016 |Segurança|O sistema deve oferecer proteção dos dados do usuario.|
|RF-017 |Processamento de vendas|O sistema deve permitir registrar as vendas realizadas na loja, incluindo informações sobre os produtos, quantidades, preços, descontos, formas de pagamento e dados do cliente |
|RF-018 |Gestão de clientes|O sistema deve oferecer um atendimento personalizado, criar programas de fidelidade e enviar comunicações direcionadas aos clientes. |
|RF-019 |Administração de promoções|O sistema deve ser capaz de monitorar o desempenho das promoções e gerar relatórios sobre sua eficácia.|
|RF-020 |Gerenciamento de estoque|O sistema deve registrar a entrada e saída de itens, realizar atualizações automáticas de estoque, gerar relatórios de inventário e alertar quando determinados produtos estiverem com baixa quantidade.|




## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Velocidade do sistema|Carregamento rápidos, processamento eficiente de consultas e capacidade de escalabilidade para lidar com aumento de demanda durante eventos ou promoções especiais. |
|RNF-002 |segurança|Segurança do sistema em relação a ataques cibernéticos |
|RNF-003 |Velocidade do sistema|O processador é um i3 de geração 9000, com 2 pentes de 4gb de memoria ram|
|RNF-004 |segurança|Segurança do sistema em relação a ataques cibernéticos |
|RNF-005 |Barra de pesquisa|Realizar um programa onde o produto desejado pelo usuário na barra de pesquisa apareça com preço e quantidade em estoque. |
|RNF-006 |Filtro de pesquisa|Realizar um sistema onde o cliente coloque um produto genérico Ex:(chuteira) apareça um catalogo somente com produto desejado.|
|RNF-007 |Filtro para Daltonicos|Ter um sistema que conta com cores para daltonismo. |
|RNF-008 |Preferências do cliente|Ter um sistema que conta com atalhos para tipo de produtos que o cliente prefere. |
|RNF-009 |Filtro do estoque|saber a quantidade de itens repetidos no estoque. |
|RNF-010 |Tema|Onde o usuario pode editar o tema da pagina. |





[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/use_case_placas.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


| REQUISITO |UC-01|UC-02|UC-03|UC-04|UC-05|UC-06|UC-07|UC-08|UC-09| UC-10|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | |
|RF-002| |X| |X| | | | | | |

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Sequências

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
