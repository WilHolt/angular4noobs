# Módulos

## Introdução

O Angular tem um próprio sistema de modularização chamado NgModules.

**NgModules** são uma espécie de container que agregam vários recursos como componentes, serviços e outros tipos de ferramentas em um escopo só, para evitar repetição e aumentando a coesão do código e também a performance.<br>
**(bem como Pacotes do Java ou Namespaces do php)**

Eles também podem se relacionar trocando por meio de exportação as funcionalidades que estão no seu escopo.

Tenha em vista que a quantidade de módulos vai depender do tamanho da sua aplicação, da complexidade, e da sua forma de estruturar.

Por exemplo: aplicações de pequeno porte podem ter apenas um módulo, já aplicações maiores podem ter modulos separados por features.

Modelo Básico de um Módulo.

```console
import { NgModule } from '@angular/core';

@NgModule({
  imports: [ ... ],
  declarations: [ ... ],
  bootstrap: [ ... ]
})
export class AppModule { }
```



## Módulos a fundo

A estrutura de um módulo se divide em


### **Decorator NgModule**
O módulo é feito a partir de um decorator chamado NgModule
dentro dele você define o que o modulo deve ter

### **Declarations**
Todos os Componentes do referido modulo devem estar declarados no campo **Declarations**, para que o modulo possa entender que aqueles componentes são somente daquele módulo.

### **Imports**
Nesta propriedade é utilizada para importar outros módulos para serem utilizados nele, definimos um array onde você declara quais modulos você quer importar.

Você só consegue utilizar algo de outro modulo se você estiver importando ele.

### **Exports**
Nesta propriedade é utilizada para importar outros módulos para serem utilizados nele, definimos um array onde você declara quais modulos você quer importar.
### **Providers**
É onde você declara quais serviços você quer injetar dentro desse módulo, ou seja, uma propriedade para injeção de dependencias.
Possibilitando treeshaking de dependencias ( Termo usado para falar sobre eliminação de codigo inutilizado ou repeticão desnecessária de código)
