# Coding Dojo Bootcamp Assignment  
## Web Fundamentals / API and AJAX / Build Your Own Pokedex

### Submit Files
```
buildyourownpokedex.html
buildyourownpokedex.css
buildyourownpokedex.js
```

### Assignment details  
How do you know which Pokemon was clicked? Maybe we can give each Pokemon a unique id that corresponds with their number in the URL?

```
<img id="2" src="http://pokeapi.co/media/img/2.png">
```

So that when the image is clicked, we get its id and add it to the end of this URL: "http://pokeapi.co/api/v2/pokemon/" then we make the ajax request with that URL that we constructed.
