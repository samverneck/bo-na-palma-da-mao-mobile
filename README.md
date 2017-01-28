# BO na Palma da Mão

O BO NA PALMA DA MÃO é um programa do Governo do Estado do Espírito Santo que reúne iniciativas e serviços do Governo em plataforma móvel (aplicativo) e web, com unidade de experiência do cidadão. Por meio do ES NA PALMA DA MÃO, diversos serviços governamentais como o proprio Bo na Palma da Mão podem ser acessados através da web e dispositivos móveis (sistemas operacionais iOS e Android) utilizando uma interface comum.

<a href="https://play.google.com/store/apps/details?id=br.gov.es.prodest.espm&referrer=utm_source%3Dgithub%26utm_medium%3Dreadme">
<img src="https://4.bp.blogspot.com/-DV3oSkBGKVw/VWdWwTZ0DSI/AAAAAAAABrs/KizNkOcUhGw/s1600/Google%2BPlay%2Blogo.png" width="200px" />
</a>

**Tabela de Conteúdo**  

- [Principais Tecnologias Utilizadas](#principais-tecnologias-utilizadas)
	- [Typescript](#typescript)
	- [angularJS](#angularjs)
	- [UI-Router](#ui-router)
	- [Ionic](#ionic)
	- [webpack](#webpack)
	- [Gulp](#gulp)
  - [Sass](#sass)
- [Visão Geral](#visão-geral)
	- [Build System](#build-system)
	- [Estrutura de arquivos](#estrutura-de-arquivos)
	- [Configuração de testes](#configuração-de-testes)
  
# Principais Tecnologias Utilizadas
Essas são as principais ferramentas, *frameworks* e *libraries* que dão suporte ao projeto:

## [Typescript](https://www.typescriptlang.org/)
TypeScript é uma linguagem para desenvolvimento JavaScript em larga escala. 
Com TypeScript podemos escrever código utilizando uma estrutura fortemente tipada e ter este código compilado para JavaScript puro. 
Nem todas as features do ES2105 já são suportados pelos browsers. TypeScript permite desfrutar de todas as novas características da linguage hoje, 
covertendo código ES2105 em código equivalente em ES5. Qualquer navegador. Qualquer host.

## [angularJS](https://angularjs.org)
angularJS é um framework estrutural para aplicações web dinâmicas.


## [UI-Router](http://angular-ui.github.io/ui-router/)
O Router nativo do Angular vem com uma série de limitações, como por exemplo a ausência de suporte para views aninhadas. UI Router permite essa e muitas
outras facilidades, e por isso tem se tornado, de fato, o router padrão das aplicações Angular.

## [Ionic](http://ionicframework.com/)
Ionic é um framework que visa a criação de aplicações híbridas para dispositivos móveis. 
Ele nada mais é do que uma pilha de componentes e outros frameworks como angularJS e ui-router.

## [webpack](https://github.com/systemjs/systemjs)

webpack é um empacotador de módulos (javascript e cia) que cria bundles de assets à partir das dependências(assets) 
do projeto.

## [Sass](http://sass-lang.com/)

SASS é uma poderosa extensão da linguagem CSS que permite uma escrita profissional e completa das folhas de estilo de forma muito 
mais dinâmica e produtiva. 

1. Permite fazer o pré-processamento de arquivos “diferentes” (coffee, es6, ts, sass, less, jade, imagens, etc) que 
os tornam “utilizáveis” através de função require() ou import(ES2015);
2. Possibilidade de carregar dependências sob demanda (code splitting), sem precisar
colocar tudo num grande e pesado bundle.

## [Gulp](http://gulpjs.com)

O automatizador de tarefas de build da aplicação.
