# Módulos

## Introdução

O Angular tem um próprio sistema de modularização chamado NgModules.

**NgModules** são uma espécie de container que agregam vários recursos como componentes, serviços e outros tipos de ferramentas em um escopo só, para evitar repetição e aumentando a coesão do código e também a performance.<br>
**(bem como Pacotes do Java ou Namespaces do php)**

Eles também podem se relacionar trocando por meio de exportação as funcionalidades que estão no seu escopo.

Tenha em vista que a quantidade de módulos vai depender do tamanho da sua aplicação, da complexidade, e da sua forma de estruturar.

Por exemplo: aplicações de pequeno porte podem ter apenas um módulo, já aplicações maiores podem ter modulos separados por features.


## Módulos a fundo

A estrutura de um módulo se divide em


Decorator NgModule

Declarations

Imporatações

Exportações

Providers
