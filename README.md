### plax
---
https://github.com/cameronmcefee/plax

```
<script type="text/javascript" src="/js/jquery.min.js"></script>
<script type="text/javascript" src="/js/plax.js"></script>

<img src="octocat.png" data-xrange="40" data-yrange="40">
<img src="earth.png" data-xrange="20" data-yrange="20">
<img src="bg.png" data-xrange="10" data-yrange="10" data-invert="true">

```

```js
$('#plax-octocat').plaxify({"xRange":40, "yRange":40})
$('#plax-earth').plaxify({"xRange":20,"yRange":20,"invert":true})
$('#plax-bg').plaxify("xRange":10,"yRange":10,"invert":true)
$.plax.enable()

$('img').plaxify()
$.plax.enable()

$plax.enable({ "activityTarget": $('#myPlaxDiv')})

$('#plax-octocat').plaxify({"xRange":40,"yRange":40})
$('#plax-earth').plaxify({"xRange":20,"yRange":20,"invert":true})
$('#plax-bg').plaxify({"xRange":10,"yRange":10,"invert":true})
$.plax.enable()

$('#my-btn').click(function(){
  $('#plax-octocat').plaxify({"xRange":200,"yRange":200})
})
```

```
```

