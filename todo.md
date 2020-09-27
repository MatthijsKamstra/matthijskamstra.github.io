# TODO

https://api.github.com/

https://api.github.com/users/matthijskamstra

https://api.github.com/users/MatthijsKamstra/repos?page=2&per_page=100%27



https://developer.github.com/v3/#pagination



https://developer.github.com/v3/#json-p-callbacks


```html
<html>
<head>
<script type="text/javascript">
function foo(response) {
  var meta = response.meta;
  var data = response.data;
  console.log(meta);
  console.log(data);
}

var script = document.createElement('script');
script.src = 'https://api.github.com?callback=foo';

document.getElementsByTagName('head')[0].appendChild(script);
</script>
</head>

<body>
  <p>Open up your browser's console.</p>
</body>
</html>
```