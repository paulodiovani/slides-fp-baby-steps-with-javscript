<!-- .slide: data-background="img/baby-steps.png" data-background-opacity=".4" data-background-size="contain" -->

## Functional Programming<br>baby steps<br>with Javascript

<small>Version 0.1.0</small>

<small>by Paulo Diovani</small>

----
<!-- .slide: id="fp-definition" class="bigtext" -->

**Functional Programming**

is a _programming paradigm_ that

treats computation as the evaluation of mathematical functions and

avoids changing-state and mutable data

====

Mutable data

```
> const zoo = [ '🐍', '🦓', '🐈', '🐻', '🐕', '🦇', '🐇' ]
> zoo.sort()
[ '🐇', '🐈', '🐍', '🐕', '🐻', '🦇', '🦓' ]
> zoo
[ '🐇', '🐈', '🐍', '🐕', '🐻', '🦇', '🦓' ]
```

Immutable data

```
> const zoo = [ '🐍', '🦓', '🐈', '🐻', '🐕', '🦇', '🐇' ]
> sort(zoo)
[ '🐇', '🐈', '🐍', '🐕', '🐻', '🦇', '🦓' ]
> zoo
[ '🐍', '🦓', '🐈', '🐻', '🐕', '🦇', '🐇' ]
```

====


![class diagram](img/class-diagram.svg) <!-- .element: class="no-border full-width" -->

====

![function block](img/function-block.png) <!-- .element: class="no-border" -->

====
<!-- .slide: data-background="img/functional-programming-word-cloud.png" data-background-size="contain" -->

----

![avatar][avatar] <!-- .element: class="avatar" -->

### Paulo Diovani Gonçalves

Technologist in Internet Systems by Feevale University.
Software Enginer at Codeminer 42.
GNU/Linux user since 2005.
<!-- .element: class="bio" -->

<table>
  <tr>
    <td>[medium/@paulodiovani][medium]</td>
    <td>[blog.diovani.com][blog]</td></tr>
  <tr>
    <td>[slides.diovani.com][slides]</td>
    <td>[@paulodiovani][twitter]</td>
  </tr>
  <tr>
    <td colspan="2" class="align-center">
      [![codeminer42][code-logo]][code-site] <!-- .element: class="no-border no-background" -->
    </td>
  </tr>
</table>

[avatar]: img/avatar.jpg
[medium]: http://medium.com/@paulodiovani
[blog]: http://blog.diovani.com
[slides]: http://slides.diovani.com
[twitter]: http://twitter.com/paulodiovani
[code-logo]: img/codeminer42.png
[code-site]: http://codeminer42.com/
