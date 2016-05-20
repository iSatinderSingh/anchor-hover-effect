# anchor-hover-effect
Anchor Hover Effect is a jQuery plugin, which makes an anchor tag fancy and animated. Currently, it provides four different types of effects .i.e Roller 3D effect, Flip Effect, Bracket Effect, and BorderBottom effect. 

Doc: http://codepedia.info/anchor-hover-effect-jquery-plugin/

## DEMO
Look at the demo section on http://codepedia.info/Anchor-hover-effect-jquery-plugin.html to see anchorHoverEffect in action.

## How to use it:
First, we need to include anchorHoverEffect.css file in our head tag. Then load anchorHoverEffect.js script after loading jQuery library.

```html
<link href="../anchorHoverEffect.css" rel="stylesheet" type="text/css" />
<script src="//code.jquery.com/jquery.min.js"></script>
<script src="../anchorHoverEffect.js"></script>
```
Add Html anchor tags whom you want to make it fancy and animated on hover.
```html
<ul class="ulDefault">
 <li><a href="#">jQuery</a></li>
 <li><a href="#">Angular Js</a></li>
 <li><a href="#">JavaScript</a></li>
 <li><a href="#">Asp.net MVC</a></li>
</ul>
```
Call the function on anchor tag you just added.
```javascript
$(".ulDefault a").anchorHoverEffect();
```

## Options:
Currently, there are four different types of effect.

* **roller3d :** is set as default, and it makes anchor tag as 3d rolling effect
* **brackets :** It added left right rectangle brackets at start and end of anchor text with animation.
* **flip :** It flips the anchor text.
* **borderBottom :** It adds border bottom with animation.

## License: MIT
