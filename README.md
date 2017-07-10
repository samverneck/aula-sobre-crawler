# aula sobre crawler

<img src="https://media.giphy.com/media/DZwCubluD5GFy/giphy.gif">

**Conceito de crawler:** Crawler, também conhecido como **Spider ou Bot**, é um robô usado pelos buscadores para encontrar e indexar páginas de um site. ... Existem ferramentas que facilitam o trabalho dos crawlers e tornam a indexação das páginas de um site mais rápida.

> Fonte: www.globalad.com.br/blog/o-que-e-crawler/

## Crawler

É um software desenvolvido para realizar uma varredura na internet de maneira sistemática através de informação vista como relevante a sua função. Eles capturam os textos das páginas e cadastram os links encontrados e assim possibilitam encontrar novas páginas. São uma das bases das Search Engines, eles são os responsáveis pela indexação dos sites, armazenando-os na base de dados dos motores de busca. Também são conhecidos como Spider ou Bot (robô).

O processo que um Web crawler executa é chamado de Web crawling ou spidering. Muitos sites, em particular os motores de busca, usam crawlers para manter uma base de dados atualizada. Os Web crawlers são principalmente utilizados para criar uma cópia de todas as páginas visitadas para um pós-processamento por um motor de busca que irá indexar as páginas baixadas para prover buscas mais rápidas. Crawlers também podem ser usados para tarefas de manutenção automatizadas em um Web site, como checar os links ou validar o código HTML. Os crawlers também podem ser usados para obter tipos específicos de informação das páginas da Web, como minerar endereços de email (mais comumente para spam).

Bom, os crawlers do buscadores geralmente procuram informações sobre permissões sobre o conteúdo. Em espcial existem duas formas de bloquear um crawler decente de indexar uma determinada página (e os links nela contidos). A primeira forma, e mais comum, é através do arquivo robots.txt. A outra forma é através da tag meta robots, com valor "noindex" ou "nofollow", usados para não indexar (a própria página) e não seguir (os links contidos na página), respectivamente. Há também uma terceira possibilidade, muito menos explorada, que é o uso do atributo rel="nofollow" em links, indicando ao crawler que aquele link em especial não deve ser seguido.

## Spider

Também conhecido como Robô, Robot, Bot ou Crawler. São programas usados pelos mecanismos de busca para explorar a internet de maneira automática e fazer download de conteúdo web de sites web. De forma metódica, não expões o conteúdo que julga irrelevante no código fonte dos sites, e armazena o resto em seu banco de dados. Deste modo, os mecanismos de busca baseados em robôs (spider ou crawlers) que vasculham a Internet atrás de informações e classificam as buscas de acordo com os links e também os conteúdos encontrados nas páginas de busca, como é o caso do maior portal de buscas da web, o Google.

Deste modo, qualquer página precisa ser rastreada pelo robô e assim, poder aparecer nos resultados de busca dos mecanismos em questão.

Segundo Thurow (2003), os robôs executam três ações básicas:

Primeiro eles acham as páginas do sítio (processo chamado spidering ou crawling) e constroem uma lista de palavras e frases encontradas em cada página;
Com esta lista eles fazem um banco de dados e encontram as páginas exatas que eles devem procurar, inserindo o sítio vasculhado no banco de dados geral organizado pelas características encontradas em suas páginas. A máquina que insere o sítio no banco de dados geral se chama indexer;
Depois disso o robô já está apto a encontrar este sítio quando o usuário final digitar na busca uma palavra ou expressão relativa ao conteúdo encontrado no sítio. Essa etapa é chamada query processor.
Como podemos perceber, por trás de qualquer busca realizada na internet, há uma série de mecanismos que trabalham unidos para fornecer um resultado satisfatório ao usuário. O processo parece um tanto complexo, no entanto, nada perceptível a nós, meros buscadores de informações.
