# Glossário - Pode Pedir FCTE

# Introdução

Um glossário, segundo o IEEE, é considerado como uma coleção de nomes e descrições narrativas de todos os termos que podem ser usados ​​para conceitos definidos dentro de um ambiente (ISO/IEC/IEEE 24765l:2024)<a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>. Ele também pode ser expandido para além dos conjuntos de descrições e termos, podendo ser adicionadas imagens, ícones, links que busquem explicar ainda mais os conceitos que estão sendo abordados <a id="anchor_2" onclick="document.getElementById('REF2').scrollIntoView()" style="cursor:pointer;">[2]</a>.

Este artefato busca organizar os termos do projeto em três diferentes glossários que se complementam. O primeiro glossário contém os termos do domínio do projeto, que são utilizados para descrever muitas vezes ações e objetos dentro do aplicativo pode pedir fcte, assim, termos como “pedido”, “código de entrega” e “informações de acesso” estarão presentes nesse glossário.

O segundo glossário apresenta os termos de arquitetura, os quais são dados pelas tecnologias utilizadas ao construir o projeto, como os frameworks e linguagens de programação, bem como conceitos da produção de um software, como “sprint” e os métodos “scrum” e “XP”.

Já o terceiro glossário consiste nos termos de versionamento do site, em que são usadas as ferramentas Git e GitHub, para isso, esse glossário busca explicar termos comuns que são utilizados ao trabalhar com essas tecnologias, como “push” e “commit”.

Por fim, para melhor organização de todos os termos e garantir uma maior rastreabilidade, são utilizados IDs para identificar cada um dos termos presentes na tabela.

<font><p style="text-align: center">**Tabela 1** - Lista de IDs do glossário e seus significados.</p></font>

| **ID**   | **Significado**                                                    |
| :--- | :------------------------------------------------------------- |
| GDXX | Termo do glossário que explica um conceito de domínio do projeto    |
| GAXX | Termo do glossário que explica um conceito de arquitetura do projeto |
| GVXX | Termo do glossário que explica um conceito de versionamento do projeto |

# Termos de Domínio

<font><p style="text-align: center">**Tabela 2** - Lista de termos de domínio do glossário.</p></font>

| **ID**    | **Termo**                  | **Significado**                                                                                                                                                               |
| :---- | :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| #GD01 | Conversas              | Corresponde a uma aba do aplicativo em que o usuário poderá se comunicar com os restaurantes em que possui pedidos em andamento ou com os entregadores.                 |
| #GD02 | Código de entrega      | Corresponde a um conjunto de quatro dígitos que poderá ser configurado pelo estudante. Por padrão, usa-se os quatro últimos dígitos do número de telefone da conta.     |
| #GD03 | Termos de Uso          |                                                                                                                                                                           |
| #GD04 | Favoritos              | Corresponde a um conjunto de restaurantes que são selecionados pelo usuário, esses restaurantes aparecem no topo das recomendações. Podem ser adicionados ou removidos livremente pelo usuário. |
| #GD05 | Informações de Acesso  | Corresponde ao email do usuário, sua senha e seu número de telefone utilizados em sua conta do aplicativo.     |
| #GD06 | Informações Pessoais   | Corresponde ao nome, email e telefone do usuário.    |
| #GD07 | Product Owners         | "Parte interessada responsável pelas capacidades, aceitação e uso de um produto." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>   |
| #GD08 | Clientes               | Corresponde ao grupo de usuários que faz pedidos no aplicativo para receberem na FCTE.                                                                            |
| #GD09 | Usuários               | Corresponde aos clientes, entregadores e restaurantes que utilizam o aplicativo.                                                                 |
| #GD10 | Esquema de avaliações  | Corresponde a um índice de 0 a 5 estrelas, em que o usuário pode escolher um número, com incrementos de meio ponto, para cada pedido que faz no aplicativo.                  |
| #GD11 | Pedido                 | Corresponde a um prato ou conjunto de pratos que foram encomendados pelo cliente para ser entregue na FCTE   |
| #GD12 | Status do Pedido       | Corresponde a um indicativo das fases em que o pedido está: em preparo, em trânsito, entregue.   |
| #GD13 | Entregador             | Corresponde a uma pessoa usuária do aplicativo que pode ou não trabalhar em um estabelecimento agregado ao aplicativo. Ela é responsável por fazer as entregas dos pedidos realizados pelos clientes. |
| #GD14 | Ponto de Entrega       | Corresponde a faculdade de ciencias e tecnologias (FCTE, antiga faculdade do gama FGA), é nela que os pedidos são feitos e são entregues.  |
| #GD15 | Suporte para o usuário | Corresponde a uma aba do aplicativo em que o usuário pode utilizá-la para inserir dúvidas e reclamações com relação aos seus pedidos/entregas, e uso do app. |

# Termos de Arquitetura

<font><p style="text-align: center">**Tabela 3** - Lista de termos de arquitetura do glossário.</p></font>

| **ID**    | **Termo**                                | **Significado**                                                                                                                                                                            |
| :---- | :----------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| #GA01 | Logado                               | Corresponde ao estado em que usuário está com suas informações cadastradas em um aplicativo e pode utilizá-lo para fazer pedidos.      |
| #GA02 | Banco de Dados                       | "Conjunto de dados organizados de acordo com uma estrutura conceitual que descreve as características dos dados e as relações entre suas entidades correspondentes, apoiando uma ou mais áreas de aplicação." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a> |
| #GA03 | API ( application programming interface) | "Conjunto de funções, protocolos, parâmetros e objetos de diferentes formatos, usados ​​para criar software que interage com os recursos ou dados de um sistema ou serviço externo." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a> |
| #GA04 | UI                                   | "Componentes de um sistema interativo (software ou hardware) que fornecem informações e controles para o usuário realizar tarefas específicas com o sistema interativo." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a> |
| #GA05 | UX                                   | "Percepções e respostas do usuário que resultam do uso ou uso antecipado de um produto, sistema ou serviço." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>                                                            |
| #GA06 | Protótipo                            | "Tipo, forma ou instância preliminar de um sistema que serve como modelo para estágios posteriores ou para a versão final e completa do sistema" (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>                             |
| #GA07 | UML (Unified Modeling Languag)       | "Linguagem gráfica para visualizar, especificar, construir e documentar artefatos de um sistema intensivo de software orientado a objetos." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>                               |
| #GA08 | BPMN                                 | "Modelo de processo de negócios e notação." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>      |
| #GA09 | Sprint                               | "Curto prazo, no qual um conjunto de recursos de software é desenvolvido, levando a um produto funcional que pode ser demonstrado às partes interessadas." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>                             |
| #GA10 | Kanban                               |                                                                                                                                                                                        |
| #GA11 | Scrum                                | "Estrutura de gerenciamento de projetos iterativo usada no desenvolvimento ágil, na qual uma equipe concorda com os itens de desenvolvimento de um backlog de requisitos e os produz em um curto período de algumas semanas." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a> |
| #GA12 | XP                                   | "Forma de desenvolvimento ágil de software em que os procedimentos para planejamento e trabalho iterativos são combinados com procedimentos técnicos, como design orientado a testes e programação em pares. (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a> |
| #GA13 | Backlog                              | "Coleção de recursos ágeis ou histórias de requisitos funcionais e não funcionais que normalmente são classificados em uma ordem com base na prioridade de valor." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>             |
| #GA14 | Product Backlog                      | "Lista de todos os requisitos, normalmente representados como histórias de usuários, que precisam ser feitos para um determinado produto." (SEVOCAB) <a id="anchor_1" onclick="document.getElementById('REF1').scrollIntoView()" style="cursor:pointer;">[1]</a>                               |

# Termos de Versionamento

<font><p style="text-align: center">**Tabela 4** - Lista de termos de versionamento do glossário.</p></font>

| **ID**    | **Termo**         | **Significado**                                                                                                                                                                                                                                                                                                                                                                                             |
| :---- | :------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| #GV01 | Pull | "Pull refere-se a quando você busca alterações e as mescla. Por exemplo, se alguém editou o arquivo remoto no qual vocês dois estão trabalhando, o ideal é fazer pull dessas alterações na cópia local para que ele fique atualizado." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV02 | Merge         | "O merge pega as alterações de um branch (no mesmo repositório ou a partir de uma bifurcação) e as aplica em outro. Normalmente, isso ocorre por meio de uma ""solicitação de pull"" (que pode ser considerada uma solicitação de mesclagem) ou por meio da linha de comando. Uma mesclagem pode ser feita por meio de uma solicitação de pull pela interface da Web GitHub.com se não há alterações conflitantes ou sempre pode ser feita por meio da linha de comando." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV03 | Branch        | "Um branch é uma versão paralela de um repositório. Está no repositório, mas não afeta a ramificação principal ou primária e permite que você trabalhe à vontade, sem prejudicar a versão ""online"". Depois de fazer as alterações desejadas, você poderá fazer uma mesclagem do branch novamente com a ramificação principal para publicar as alterações." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV04 | Issue         | "Problemas são sugestões de melhorias, tarefas ou perguntas relacionadas a um repositório. Podem ser criados por qualquer pessoa (em repositórios públicos) e são moderados por colaboradores de repositórios. Cada problema contém um thread próprio de discussão. Você também pode categorizar um problema com rótulos e atribuí-lo a alguém." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV05 | Git   | "O Git é um programa de código aberto para acompanhamento de alterações em arquivos de texto. Ele foi escrito pelo autor do sistema operacional Linux e é a principal tecnologia na qual o GitHub, a interface social e do usuário, se baseia." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV06 | Push          | "Quando você envia um branch por push com sucesso para um repositório remoto, o branch remoto é atualizado com as alterações do branch local. Quando você ""envia um branch por push"", o Git procura a referência de HEAD do branch no repositório remoto e verifica se ela é um ancestral direto da referência de HEAD do branch local. Após a verificação, o Git efetua pull de todos os objetos (acessíveis pela referência de HEAD local e ausentes do repositório remoto) no banco de dados de objetos remoto e atualiza a referência de HEAD remoto. Se o HEAD remoto não é um ancestral do HEAD local, ocorre uma falha na operação de push." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV07 | Conflito de mesclagem | Uma diferença que ocorre entre branches mesclados. Os conflitos de mesclagem acontecem quando as pessoas fazem alterações diferentes na mesma linha do mesmo arquivo ou quando uma pessoa edita um arquivo e outra pessoa exclui o mesmo arquivo. O conflito de mesclagem precisa ser resolvido para que você mescle os branches." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV08 | Markdown | "O Markdown é um formato de arquivo de semântica incrivelmente simples, não muito diferente do .doc, do .rtf e do .txt. O markdown facilita a escrita em prosa (com links, listas, marcadores etc) e a sua respectiva publicação como apresentado em um site, mesmo para aqueles que não têm conhecimento sobre como publicar na web." (GitHub glossary)  <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a>|
| #GV09 | Repositório   | "Um repositório é o elemento mais básico do GitHub. É mais fácil imaginá-lo como uma pasta de projetos. Um repositório contém todos os arquivos de projeto (incluindo a documentação) e armazena o histórico de revisão de cada arquivo. Os repositórios podem ter vários colaboradores e podem ser públicos ou privados." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV10 | Review        | "As revisões permitem que pessoas com acesso ao seu repositório comentem as alterações propostas em pull requests, aprovem as alterações ou solicitem outras alterações antes do merge da pull request." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |
| #GV11 | Pull Request  | "Pull requests são alterações propostas em um repositório enviadas por um usuário e que são aceitas ou rejeitadas pelos colaboradores do repositório. Assim como problemas, as pull requests têm seus próprios fóruns de discussão." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a>|
| #GV12 | GitHub Pages  | "Também conhecido como Pages. Um serviço de hospedagem de site estático desenvolvido para hospedar suas páginas pessoais, da organização ou de projeto diretamente em um repositório do GitHub." (GitHub glossary) <a id="anchor_3" onclick="document.getElementById('REF3').scrollIntoView()" style="cursor:pointer;">[3]</a> |

# Referências

> <span id="REF1">1.</span> <a onclick="document.getElementById('anchor_1').scrollIntoView()" style="cursor:pointer;">Software and Systems Engineering Vocabulary (SEVOCAB). Disponível em:</a>: https://pascal.computer.org/sev_display/index.action. Acesso em: 02 de setembro de 2025;

> <span id="REF2">2.</span> <a onclick="document.getElementById('anchor_2').scrollIntoView()" style="cursor:pointer;">Arquitetura e desenho de software, aula - projeto e desenho de software. Disponivel em:</a>: https://aprender3.unb.br/pluginfile.php/3178378/mod_page/content/5/Arquitetura%20e%20Desenho%20de%20software%20-%20Aula%20Projeto-DSW%20-%20Profa.%20Milene.pdf. Acesso em: 02 de setembro de 2025;

> <span id="REF3">3.</span> <a onclick="document.getElementById('anchor_3').scrollIntoView()" style="cursor:pointer;">Glossário do GitHub. Disponível em:</a>: https://docs.github.com/pt/get-started/learning-about-github/github-glossary. Acesso em: 02 de setembro de 2025.

 

# Histórico de Versões

| **Data**       | **Versão** | **Descrição**                         | **Autor**                                      | **Revisor**                                      | **Data da Revisão** |
| :--------: | :----: | :-------------------------------- | :----------------------------------------: | :----------------------------------------: | :-------------: |
| 03/09/2025 |  `1.0`   | Criação do documento do Glossário e adição os termos. | [`@Luiz`](https://github.com/luizfaria1989) | [`@`](https://github.com/) |   00/00/0000    |
| 03/09/2025 |  `1.1`   | Adições de referências para o documento. | [`@Luiz`](https://github.com/luizfaria1989) | [`@`](https://github.com/) |   00/00/0000    |
| 04/09/2025 |  `1.2`   | Remoção de termos sem significados do glossário. | [`@Luiz`](https://github.com/luizfaria1989) | [`@`](https://github.com/) |   00/00/0000    |