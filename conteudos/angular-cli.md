
## Angular CLI
Primeiramente depois de tudo configurado, vamos precisar entender como funciona o Angular CLI
Para Instalar utilizaremos o NPM que é um gerenciador de Pacotes do NodeJS, digitando o seguinte código
 ```console 
     npm install -g  @angular/cli
 ```

Angular CLI e uma poderosa ferramenta de gerenciador de linhas de Comandos onde voce pode gerenciar toda a aplicacão atraves das linhas de comando do prompt de comando do seu sistema operacional
**certo, mas o que ele me ajuda?**
> Ele nos ajuda a criar o proprio projeto, modulos, servicos, components diretivas, entre outras coisas de forma facil, rápida e padronizada.

**Mas Como ele Funciona?**
> É facil, basta usar a nomeclatura que ele te proporciona que e o comando: NG e seus comandos

vou te dar uma lista dos comandos e em seguida te ensinar como usar cada um


| Comando        | O que ele faz |
| ------------- |:-------------:|
| col 3 is      | right-aligned |
| col 2 is      | centered      |
| zebra stripes | are neat      |

1. * ng new  
> Cria o Projeto instalando todas as dependencias atraves do Package.json e Angular.json
2. ng generate component [nomedocomponent]- cria um componente, gerando o componenet.ts, o component.spec.ts (para testes)
3. ng generate module  [nomedomodule]- cria um modulo na pasta escolhida com o nome escolhido
4. ng generate service  [cria um servico]
5. ng generate directive [ cria uma diretiva]
