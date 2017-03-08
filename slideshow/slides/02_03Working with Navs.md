<!-- .slide: data-state="title" -->
# Bootstrap 4
Upgrading Navs

>> Speaker Notes:
Navs were pretty simple in Bootstrap 3 and they're a good example of a component that got a bit of an upgrade because of flexbox. A lot has stayed the same, but there's a bit more markup now and it's easier to lay navs out now.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Basic Nav Classes
<ul>
	<li class="fragment">With/without `UL`s</li>
	<li class="fragment">`nav`</li>
	<li class="fragment">`nav-item`</li>
	<li class="fragment">`nav-link`</li>
</ul>


>> Notes:
1. If you go by the old documentation, all of your navs are probably list items, the new navs work with lists or regular divs.
2.  Just like before, the main class is the nav class
3. Because it works with and without lists, now you have to add a nav-item to each item.
4. If the nav has a link, you also add a class of nav-link. If you're using anchor tags without list items, you can use both the nav-item and the nav-link classes in the anchor tags.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Nav Alignment
<ul>
	<li class="fragment">`justify-content-center`</li>
	<li class="fragment">`justify-content-end`</li>
	<li class="fragment">`nav-fill`</li>
	<li class="fragment">`nav-justified`</li>
	<li class="fragment">`flex-column`</li>
</ul>

>> Notes:
1. Because the nav is now flexbox based, you can easily control the alignment of the navigation easily with flexbox classes. So now, centering the nav is a cinch with justify-content-center
1. In the same way, you can easily align the nav to the right with justify-content-end.
1. There's a couple of styles to force your nav to take up all the available horizontal space. nav-fill will make the links fit the horizontal space, but the space of each link will be different depending on the width of the text.
1. If you want the spacing between the links to be the same, you can use nav-justified.
2. Finally, you can use flex-column at different breakpoints to make your nav easily responsive.

```
<nav class="nav nav-pills flex-column flex-sm-row">
  <a class="flex-sm-fill text-sm-center nav-link active" href="#">Active</a>
  <a class="flex-sm-fill text-sm-center nav-link" href="#">Link</a>
  <a class="flex-sm-fill text-sm-center nav-link" href="#">Link</a>
  <a class="flex-sm-fill text-sm-center nav-link disabled" href="#">Disabled</a>
</nav>
```

# Conclusion
If you were using the previous version of this framework, you'll immediately notice that the new navigation is simpler with lots of layout options. The addition of flexbox is the engine that makes this possible.