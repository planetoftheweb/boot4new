<!-- .slide: data-state="title" -->
# Bootstrap 4
Buttons &amp; Button Groups

>> Speaker Notes:
Not much has changed with buttons or button groups, but there are a couple of minor issues to watch out for when upgrading.
---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-hand-o-up"></i> Button Changes

<ul>
	<li class="fragment">`btn-default` >  `btn-secondary`</li>
	<li class="fragment">No `btn-xs`</li>
	<li class="fragment">No `btn-group-xs`</li>
	<li class="fragment">No spacing on groups</li>
</ul>

>> Speaker Notes:
1. The main change you'll need to worry about is if you have any buttons with the class ban-default, that class now has the name of ban-secondary.
2. There is also no btn-xs class. The new btn-sm class is quite small, so the xs class is no longer necessary.
3. There is no explicit spacing of elements, so like with other elements, you should use the spacing and margin classes.

## Conclusion
Buttons or button groups aren't going to be a big problem when upgrading...just a couple of small class changes to worry about.