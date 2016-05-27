# Love your Code
## We are designers. And we love to code.

### Manifest
If you look closely, all around you a lot of people are doing amazing things in the name of Love.. Love for their families, Love for the sport, Love for the nature.

###We do it everyday, for the Love for Code.

This is an ode for the "Rare Unicorn", an ode for that "One Man Show", an ode for all of us that were born as designers but learned to code just for love.

###Support
Show your love to your code using the small tagline at your footer, header, sidebar, well.. you are a designer. We don't need to tell you where you should put it.

####Using the SVG tag 
######(thanks <a href="http://twitter.com/julianlengfeldr" target="_blank">@julianlengfeldr</a>!)
First you insert the SVG ( or paste the svg code inline ) 

```
<div class="snippetbox">
  <p><a href="assets/love-your-code.png">get the svg</a></p>
</div>
```
Then apply some css to it:
```
<div class="snippetbox">
  <p>.heart { color: red; }</p>
</div>
```

and some extra points if you animate it:
```
.heart { 
  color: red; 
  transform-origin: 50% 50%; 
  transform: scale(.9); 
  animation-name: beat; 
  animation-duration: 1s; 
  animation-delay: .35s; 
  animation-iteration-count: infinite; 
  animation-timing-function: ease-in-out; 
  animation-play-state: running; 
  animation-fill-mode: forwards; 
}

@keyframes beat {
  0% {
    transform: scale(.9);
  }
  15% {
    transform: scale(.93);
  }
  30% {
    transform: scale(.88);
  }
  45% {
    transform: scale(.93);
  }
  60% {
    transform: scale(.9);
  }
}
```

####Using font awesome</h4>
First you include the <a href="https://fortawesome.github.io/Font-Awesome/icons/" target="_blank">FontAwesome</a> link at the head of your site.
Then add the snippet:

```
<div class="loveyourcode">
  <i class="fa fa-heart"/>
  <i class="fa fa-code"/>
</div>
```
and a little bit of css to complete the trick:
```
.loveyourcode i { font-size: 15px; }
.loveyourcode i.fa-heart { color: red; }
```

Remember to place it whatever you like and <a href="mailto:cb@hashboxed.com">send your link</a>, so we can feature you in the hall of fame. Also feel free to collaborate on <a href="https://github.com/gugote/loveyourcode">github</a>.

###### hashboxed.com - 2016 
