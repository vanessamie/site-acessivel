# Acessibilidade Web

Site "Apeperia", utilizado durante Trilha Front-End, curso:
- Acessibilidade web parte 1: tornando seu front-end inclusivo.

##

- https://vanessamie.github.io/site-acessivel/

##

## Conceitos aprendidos:

- Leitores de tela;
- Forma como deficientes visuais navegam pela internet;
- Configuração do NVDA;
- Semântica do HTML;
- Boas práticas;
  - Utilizar somente um h1;
  - Padronizar as divs;
  - Adicionar um link para ir ao conteúdo principal (e pular as opções do Menu);
  - alt nas imagens que possuem função de conteúdo, escrever de maneira descritiva, evitando redundâncias;
  - colocar o elemento <title> em SVGs que forem inline (código direto no HTML).
  - Separar o que é visual do que é conteúdo;
    - Colocar o que é visual no CSS;
    - list-style: none;
    - utilizar :after e :before para as estilizações de listas;
  - SEO vs Acessibilidade;
  - lang (configurar o idioma principal do documento, )
  - Display "none" e visibility "hidden" não são lidos, utilizar position "absolute" ou "relative" e margin "left" ou "right" 9999px, opacity "0" para deixar o conteúdo escondido;
  - Evitrar submenus;
  - WAI-ARIA;
  - atribulo role;
  - <figure>;
  - <figcaption>;
  - aria-labelledby;
  - Em formulários:
    - <input>;
    - <label>;
    - for;
    - id;
    - readonly;
- Inserção de legenda com <track>;
  - kind="subtitles";
  - srclang="pt-br";
  - label="Português(Brasil)"
  - Criação de arquivo de legenda;
- <iframe>.


##

### Observações

###### Criei o arquivo "base.css", importando a url de todos os arquivos *.css, deixando o <head> mais organizado.

###### Eu não desenvolvi o site! HTML e CSS foram disponibilizados pelo instrutor! O intuito do curso era aprender e desenvolver um site acessível para deficientes visuais, com um bônus da legenda do vídeo, para acessibilidade de deficientes auditivos!

##

Em caso de sugestão ou alguma alteração, fiquem a vontade para entrar em contato! Toda contribuição é bem-vinda!

Gratidão a ONE, Alura e Instrutor Natan Souza.

##

### Materiais interessantes:

-  Pesquisa da WebAIM sobre o uso de leitores de tela:
https://webaim.org/projects/screenreadersurvey7/

- NVDA (donwload do software):
https://www.nvaccess.org/

- Pacotes de idiomas do NVDA para Windows:
https://support.microsoft.com/pt-br/windows/pacotes-de-idiomas-para-o-windows-a5094319-a92d-18de-5b53-1cfc697cfca8

- Lista de leitores de tela da Wikipedia:
https://en.wikipedia.org/wiki/List_of_screen_readers

- Acessibilidade - por que deixarmos de ser amadores para um público que espera mais de nós (SlideShare):
https://pt.slideshare.net/MarinaDomingues7/acessibilidade-por-que-deixarmos-de-ser-amadores-para-um-pblico-que-espera-mais-de-ns

- Pesquisa sobre o uso de leitores de tela:
https://www.estudoinclusivo.com.br/

- Frontinsampa 2016 - Talita Pagani: Acessibilidade na prática para você nunca mais esquecer:
https://www.youtube.com/watch?v=4URTZHk6tz0

- Pesquisa e matéria sobre "Acessibilidade, SEO e SVG":
http://reinaldoferraz.com.br/acessibilidade-seo-e-svg/

- Conteúdo invisível apenas para usuários de leitores de tela (Inglês):
https://webaim.org/techniques/css/invisiblecontent/

- Teclas de atalho para NVDA:
https://webaim.org/resources/shortcuts/nvda

- Checar a visualização das cores utilizadas:
https://contrastchecker.com/

- WAI-ARIA:
https://developer.mozilla.org/en-US/docs/Learn/Accessibility/WAI-ARIA_basics#what_is_wai-aria

- Lista com "role" existentes:
https://www.w3.org/TR/wai-aria/

- Atalhos básicos de leitores de tela para testes de acessibilidade (inglês):
https://www.tpgi.com/basic-screen-reader-commands-for-accessibility-testing/

- Frontinsampa 2015 - Vanessa Me Tonini: WAI-ARIA: Acessibilidade em tempo real:
https://www.youtube.com/watch?v=l_NBdzqYm44

- Plugin HandTalk:
https://www.handtalk.me/br/

