# BRStrap v0.5

BRStrap é o framework da comunidade Drupal Brasil para a criação de sites/portais do Governo da Rupública Federativa do Brasil.
Seu propósito é que o trabalho in-house e de contribuidores/fornecedores seja consistente estética e funcionalmente.

BRStrap está basado no [Bootstrap v2.3.1](http://twitter.github.com/bootstrap)


## Compilar o CSS e JavaScript

BRStrap inclui um [makefile](Makefile) para compilar o framework. Antes de começar instale [as dependências locais requeridas](package.json):

```
$ npm install
```

Uma vez que estejam instaladas, você poderá usar os seguintes comandos:

#### build - `make`
  Execurta o compilador recess para construir os arquivos `/less` e compila os docs. Requere recess e uglify-js.

#### watch - `make watch`
Este método revisa os arquivos Less e os compila automaticamente quando são salvos. Requer Watchr.


## Créditos

Este projeto é baseado no [BAStrap](http://gcba.github.com/BAstrap)


### Autores originais

**Mark Otto**

+ [http://twitter.com/mdo](http://twitter.com/mdo)
+ [http://github.com/mdo](http://github.com/mdo)

**Jacob Thornton**

+ [http://twitter.com/fat](http://twitter.com/fat)
+ [http://github.com/fat](http://github.com/fat)


## Copyright and license

Copyright 2012 Twitter, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
