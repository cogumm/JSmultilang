multilang
================

Usando multi linguas de maneira fácil e rápido com o jquery.


Uso
=====

* Basta colocar o atributo tkey em cada elemento que deseja traduzir:

```html
<p tkey="string-key-example"></p>
```


* Para tradução, basta editar o arquivo .json, para cada texto de tradução uma linha:

```json
"string-key-example" : "Example string in English"
```

```json
"string-key-example" : "Exemplo de texto em Português"
```


* Para carregar, basta adicionar o lang.js no final do seu arquivo HTML:

```html
<script src="http://code.jquery.com/jquery-1.11.0.min.js"></script>
<script src="lang.js"></script>
```
