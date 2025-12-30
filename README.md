# HTML

Hypertext (Hipertexto)
Markup (Marcação)
Language (Linguagem)

## O que é o HTML?

- É linguagem de programação? Não
- `tags` (marcação)
- Links para outros textos
- Imagens, sons e vídeos
- Arquivo com a extensão `.html`

## Anatomia das tags

- Abertura de tag
- Conteúdo
- Fechamento de tag
- Elementos
- Atributos

```
<h1 id="title">Título<h1>
```

- Elementos vazios
- Não possuem conteúdo
- Poderão conter atributos

```
<img src="" alt="" />
<br />
```

## Comentários

- Ignorar o texto no código

```
<!--
 Comentário aqui
-->
```

## Fluxo HTML

- Block

```
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc non felis vitae massa sagittis sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc non felis vitae massa sagittis sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
```

- Inline

```
<p>Lorem ipsum dolor sit amet, <a href="#">consectetur</a> adipiscing elit. Nunc non felis vitae massa sagittis sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc non felis vitae massa <a href="#">sagittis</a> sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
```

## Aninhamento de tags

```
<p>Lorem ipsum dolor sit amet, <em>consectetur</em> adipiscing elit. Nunc non felis vitae massa <a href="#">sagittis</a> sagittis. Vivamus id mauris laoreet, <strong>sollicitudin</strong> lectus id, sagittis metus.</p>
```

## Atributos HTML

- Informações extras
- Configurações

```
<img src="" alt="" />
<a href="#">Link</a>
```

### ID

- Atributo de identificação única

```
<div id="nome-1"></div>
<div id="nome-2"></div>
```

### Class

- Atributo de classificação, podendo conter em mais de uma tag

```
<div class="produto tenis">Tênis</div>
<div class="produto camiseta">Camiseta</div>
```

### Data-

- Atributo personalizado podendo ser utilizado no JS

```
<div data-qualquer-coisa="1234"></div>
```

### Style

- Atributo de estilo CSS

```
<div style="color: blue;">Título</div>
```
