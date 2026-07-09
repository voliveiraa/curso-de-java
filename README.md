Utilizando esse projeto dedicado a estudos em JavaScript.

# Comentários

- para comentários em uma unica linha

## /_ e _/ para comentários em multiplas linhas

# Variaveis

/\* Variaveis são espaços de memória que armazenam valores, podendo ser alterados durante a execução do programa.Similares a analogia de espaço em um estacionamento.
Pode utilizar a palavra let em vez de var, pois ela é mais moderna e possui algumas vantagens, como o escopo de bloco.
Assim como nos estacionamentos, podemos criar variaves de tamanhos diferentes. cada linha é uma string, e cada coluna é um caractere. podemos criar variaveis de diferentes tipos, como string, number, boolean, array, object, etc.
As formas de delimitar uma string são: aspas simples, aspas duplas e crase. cada uma tem suas particularidades, mas todas funcionam da mesma forma. podemos utilizar variaveis dentro de strings utilizando a crase e o ${} para interpolação de variaveis.
O nome de cada veriavel e denominado por idendtificador a priemira regra e que elas pode inciar com uma letra com um $ ou com um \_, náo pode comecar com numeros, possivel utilizar acentos e simbolos, náo podem contrar espacos, náo podem ser palavras reservadas.

Primitivos primordiais - Number - string - boolean

number
infinit
NaN
string
boolean
null
undefined
object
array
function

// Comando para saber as variaveis qual voce está utilizando é usar o typeof "variavel"
\*/

## // = é usado para atribuir valores a variaveis

# instalar o node.Js

nvm install node

## // Confirmar a versão do node - 

node -v

# para que serve o +

// + para adição - para o javascript entender que ele é um numero para adição, é nescessario adicionar um (number + number)
// + para concatenação - no caso da concatenação seria (string + string)

# Conversão de number para string

// existem duas maneiras String(n) ou n.toStrin()

# Formatação de novas strings 

// Por exemplo, eu crio uma variavel com a letra s (var s = 'JavaScript')

Antigamente era utilizado - 

> idade = 35
35
> nota = 5,5
5
> nome = "vitor"
'vitor'
> ' O aluno ' + nome + ' com idade' + idade + ' tirou a nota ' + nota
' O aluno vitor com 35 tirou a nota 5'

Agora é utilizado de outra maneira mais facil - 

// Utilizando o ${s} entre crases 

> `O aluno ${nome} com idade ${idade} tirou a nota ${nota}`
'O aluno vitor com idade 35 tirou a nota 5'

// Outras coisas com a variavel s
//s.lenght - quantos caracteres a string tem
//s.toUpperCase() - tudo para maiuscula
//s.toLowerCase() - tudo para minuscula
