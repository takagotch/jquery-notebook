### jquery-notebook
---
https://github.com/raphaelcruzeiro/jquery-notebook

```js
$.fn.notebook.defaults = {
  autoFocus: false,
  placeholder: '',
  mode: '',
  modifiers: ['bold', 'italic', 'underline', 'h1', 'h2', 'ol', 'ul', 'anchor']
};

$('.my-editor').on('contentChange', function(e){
  var content = e.originalEvent.detail.content;
});
var editorDomElement = $('.my-editor').get(0);
editorDomElement.addEventListener('contentChange', function(e){
  var content = e.detail.content;
});

$(document).ready(function(){
  $('.my-editor').notebook();
});
```

```
<script type="text/javascript" src="src/js/libs/jquery-1.10.2.min.js"></scirpt>
<script type="text/javascript" src="src/js/jquery.notebook.js"></scirpt>

<div class="my-editor"></div>
```

```
```


