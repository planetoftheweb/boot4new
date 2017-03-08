<!-- .slide: data-state="title" -->
# Bootstrap 4
Upgrading Navbars

>> Speaker Notes: Navbars are almost a totally new component in Bootstrap and upgrading them will seem really difficult at first. Let's take a look at how it works.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> What's Different
<ul>
	<li class="fragment">Simpler classes</li>
	<li class="fragment">Easier to style</li>
	<li class="fragment">Simpler responsiveness</li>
	<li class="fragment">More markup</li>
</ul>


>> Notes:
1. The classes are much simpler to use and they make more sense...for example, there is no longer a navbar-header class and it's much easier to create a hamburger menu with a single span.
2.  Navbars are also much easier to style. The main navbar class is all you need to target to style your navs and you can use the bg-color classes to change the color of your backgrounds. 
3. Making the nav responsive is also easier and you don't have manually add a little dropdown caret span. Aligning elements is also a bit simpler with flexbox.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Navbar Styles
<ul>
	<li><p contenteditable>`bg-COLOR` for backgrounds</p>
		<small style="line-height: 220%; vertical-align: text-bottom;"><code style="background:#0275d8; color:white;">primary</code> <code style="background:#5cb85c; color:white;">success</code> <code style="background:#5bc0de; color:white;">info</code> <code style="background:#f0ad4e; color:white;">warning</code><br> <code style="background:#D9534E; color:white;">danger</code> <code style="background:#292b2c; color:white;">inverse</code>  <code style="background:#f7f7f7; color:black;">faded</code></small>
	</li>
	<li class="fragment">`navbar-light`</li>
	<li class="fragment">`navbar-inverse`</li>
</ul>

>> Notes:
1. The main navbar is much easier to style. You can simply use a bg-color class to change the color of the background, and if you don't like those colors, you can use CSS to easily change the bg colors.
2. There are two additional classes for controlling the color of the text. If your background is going to be lighter, you can use the navbar-light class and the text will be darker.
3. if your background will be darker, you can use navbar-inverse class and your text will be lighter.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Responsiveness
<ul>
	<li class="fragment"><p contenteditable>`navbar-toggleable-BP`</p>
		<small style="line-height: 220%; vertical-align: text-bottom;">
			<b>BP:</b> <code style="background:#5cb85c; color:white;">sm</code> >576px 
			<code style="background:#5cb85c; color:white;">md</code> >768px 
			<code style="background:#5cb85c; color:white;">lg</code> >992px 
			<code style="background:#5cb85c; color:white;">xl</code> >1200px
		</small><br>
	</li>
	<li class="fragment">No `navbar-header`</li>
	<li class="fragment">`navbar-toggle` > `navbar-toggler` </li>
	<li class="fragment">no `collapsed` </li>
</ul>

>> Notes:
1. To make a navbar responsive, you need to specify when the navigation will become responsive using the navbar-toggleable class.
2. You no longer have to create a navbar-header, to insert a brand.
3. The navbar-toggle class is now called navbar toggle.
4. There isn't a collapsed class anymore, it's no longer necessary.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Navbar Classes
<ul>
	<li class="fragment">`nav-item`</li>
	<li class="fragment">`nav-link`</li>
	<li class="fragment">`form-inline`</li>
</ul>

>> Notes:
1. Every navigation element needs two classes a navies class. If you're using list items, then this goes on the list items.
2. Also nav-link class for the links. Those are new, so they have to be added.
3. If you're adding a form, the class to use is not form-inline and you can use the regular alignment classes to align and space elements. Make sure you watch the video on Element Spacing and Utilities for more info.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Dropdowns
<ul>
	<li class="fragment">`a` or `button` Dropdowns </li>
	<li class="fragment">No caret</li>
	<li class="fragment">`dropdown-item`</li>
	<li class="fragment">`dropdown-divider`</li>
</ul>

>> Notes:
1. If you're using a dropdown, you'll need to make sure those are simple buttons or anchor tags. List items no longer work.
2. You don't need to manually add a caret character anymore.
3. Each anchor tag gets a dropdown-item class
4. finally the dividers are now called dropdown-divider instead of just dropdown


![Diff](https://dl.dropboxusercontent.com/s/kmp9jqm148ep5xo/2017-02-11%20at%209.46%20PM.png)

# Conclusion
The new navigation is simpler, but it does take additional classes. If you're updating your navigation the huge changes are the main navbar classes as well as the responsive classes and dropdowns.