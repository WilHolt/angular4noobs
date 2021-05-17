
## Angular CLI
Primeiramente depois de tudo configurado, vamos precisar entender como funciona o Angular CLI
Para Instalar utilizaremos o NPM que é um gerenciador de Pacotes do NodeJS, digitando o seguinte código

 ```console 
     npm install -g  @angular/cli
 ```

Angular CLI e uma poderosa ferramenta de gerenciador de linhas de Comandos onde voce pode gerenciar toda a aplicacão atraves das linhas de comando do prompt de comando do seu sistema operacional
**Certo, mas em que ele me ajuda?**
> Ele nos ajuda a criar o proprio projeto, módulos, servicos, componentes,  diretivas, entre outras coisas de forma facil, rápida e padronizada.

**Mas Como ele Funciona?**
> É facil, basta usar a nomeclatura que ele te proporciona que e o comando: ng e seus comandos

vou te dar uma lista dos comandos e em seguida te ensinar como usar cada um


| Comando        | O que ele faz |
| ------------- |:-------------:|
| ng new     | Cria o Projeto instalando todas as dependencias e criando os arquivos |
| ng generate| cria ou atualiza componentes, modulos, servicos e diretivas (component, module, service, directive )      |
| ng build  | gera o build de produção para sua aplicação |
| ng serve  | Gera e serve a aplicação em localhost |
| ng test   | roda os testes unitários da aplicação |
| ng update  | atualiza a aplicação e suas dependencias |
| ng version  | mostra a versão do Angular CLI |


### Alias
Você pode rodas os comandos por alias para os que possuem alias.
**Exemplo**
```console
ng generate component my-component
````
```console
ng g c my-component
````

lista

Para ver mais detalhes de cada comando você pode rodar o comando ```--help```


