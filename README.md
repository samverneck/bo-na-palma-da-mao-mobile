# BO na Palma da Mão

**Tabela de Conteúdo**  

- [Principais Tecnologias Utilizadas](#principais-tecnologias-utilizadas)
	- [Typescript](#typescript)
	- [angularJS](#angularjs)
	- [UI-Router](#ui-router)
	- [Ionic](#ionic)
	- [webpack](#webpack)
	- [Gulp](#gulp)
  - [Sass](#sass)

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

## Plugins [IONIC2] (https://ionicframework.com/docs/v2/native/)

* https://ionicframework.com/docs/v2/native/geolocation/
	- ionic plugin add cordova-plugin-geolocation
	
* https://ionicframework.com/docs/v2/native/google-maps/
	- ionic plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID="YOUR_ANDROID_API_KEY_IS_HERE" --variable API_KEY_FOR_IOS="YOUR_IOS_API_KEY_IS_HERE"

Repo: https://github.com/apache/cordova-plugin-geolocation
Repo: https://github.com/mapsplugin/cordova-plugin-googlemaps
 
