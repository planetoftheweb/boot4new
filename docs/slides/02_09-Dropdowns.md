<!-- .slide: data-state="title" -->
# Bootstrap 4
Dropdowns

>> Speaker Notes:
Dropdowns in the new version of bootstrap use different tags and classes, so let's take a look at what you have to watch out for during migration.

---

## Dropdown Changes

<ul>
	<li class="fragment">Use `a` or `button`</li>
	<li class="fragment">`dropdown-item`</li>
	<li class="fragment">No caret necessary</li>
	<li class="fragment">`divider` > `dropdown-divider`</li>
</ul>

>> Speaker Notes:
1.  Although dropdowns are simpler to build, there is a bit more markup. They can be built using anchor tags and buttons now, so there is less structural markup.
2. You now have to add a dropdown-item class on every item.
3. You no longer have to include a caret character to indicate the dropdown.
4. The divider class has changed a bit from just divider to dropdown-divider

## Conclusion
I like some of the changes in the new dropdowns, It's easier using less markup although you end up using a few more classes for the items.

https://dl.dropboxusercontent.com/s/u1g5imetwthxsmi/2017-02-12%20at%208.40%20PM.png