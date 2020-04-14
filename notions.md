## Quando tiver mais de um device

- Rodar flutter run -d "Nome do Emulador"

Flutter é divido por 2 widget

StatelessWidget e StatefulWidget

StatelessWidget ele não tem estado, é só um desenho na tela

StatefulWidget ele mantém o estado

StatelessWidget ele não permite que chame um componente para renderizar a tela(ele não tem estado)

## Diferenças entre stateless e stateful

stateful começa com um método createState, ele instancia uma classe e passa como parametro essa classe

## Criando Widgets

Snippets: stl e stf

## Método Build

Constrói o layout

## Scaffold

Representa uma página, ou seja, sempre que tiver uma página terá um scaffold

Scaffold -> esqueleto da página

Scaffold -> body e appBar

## appBar

Tem o Leading que vai antes do title do appbar e o action que vai dps do title

## Convertendo JSON para DART

Entrando no site JSON TO DART

url: https://javiercbk.github.io/json_to_dart/

apenas colocando o valor json no textarea e clicando genrate Dart ele converte
automaticamente

## ListView

Criar um ListView.builder pois ele percorre os items sobre demanda, não irá ter uma lista fixa de items

itemCount -> ele pega o tamanho ou quantidade de items

itemBuilder -> é uma função, ele vai construir os items na tela

## SetState

Só está disponivel no stateful

Ele fala quais items ele tem que alterar

## TextFormField

keyboardType: TextInputType.phone -> o teclado fica com numeros de celular

keyboardType: TextInputType.emailAddress -> o teclado fica com o @ no canto inferior esquerdo

## Removendo Item

Dismissible é um widget que da um efeito de arrastar pro lado
bastante usado para excluir itens

## Instalando Pacotes

pubspec.yaml -> dependencies -> é onde instala os pacotes

## Lendo Itens

Quando for usar uma biblioteca ou usar para acessar dados, nunca vai ser em tempo real, vai retornar sempre uma promisse, ou seja, se usa async

e no Flutter existe o Future que é a mesma coisa que uma promisse

### Dependencia

shared_preferences
