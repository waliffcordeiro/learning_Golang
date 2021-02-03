___

<center>Golang</center>

___


## Go Playground
Ambiente para desenvolvimento sem necessidade de nenhuma preparação de workspace
https://play.golang.org/

___

## Package e Import
O package é utilizado para definir qual lib é aquele arquivo (package main define aquele arquivo como principal), o import inclui libs no sistema. 
Sintaxe básica de um hello world:
~~~golang
package main

import (
	"fmt"
)

func main() {
	fmt.Println("Hello, playground")
}
~~~
Println retorna o número de caracteres e se houve erro.
Em Go não é permitido declarar variáveis que não são utilizadas, para isso podemos utilizar, por exemplo, o _ no retorno de funções.
___

## Variáveis, valores e tipos
Para declara em Go, utiliza-se o operador := (marmota ou gopher) que possui tipagem automática.
Para atribuir, utiliza-se o sinal de igual (=)

~~~golang
package main

import (
	"fmt"
)

func main() {
	x := 10
	fmt.Printf("x: tem o valor %v e o tipo %T", x, x)
}
~~~
O código acima exemplifica um código que obtém o valor e tipo de uma variável

A marmota (:=) só funciona dentro de codeblocks {}, para declarações em escopo de package podemos usar **var**
___

## Keywords
golang.org/ref/spec#keywords
 ' |  '| '
| ------------- |:-------------:| -----:|
|break       | default    |   func     |   
|interface   | select     |    if      |
|case        | defer      |    go      |
|map         | struct     |   import   |
|chan        | else       |   goto     |   
|package     | switch     |   type     |
|const       | fallthrough|   return   |   
|range       |   for      |    var     |
|continue    |
___

## 


___