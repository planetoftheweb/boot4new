<!-- .slide: data-state="title" -->
# Bootstrap 4
Tables

>> Speaker Notes:
Tables are one of my favorite features in Bootstrap because it makes something that's fairly complex to code, super easy. There's just a few changes and things to watch out for when you're migrating your tables to this new version.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-table"></i> Table Classes

<ul>
	<li class="fragment">`table-inverse`</li>
	<li class="fragment">`thead-inverse`</li>
	<li class="fragment">`table-responsive`</li>
</ul>

>> Speaker Notes:
1. There's a few additional classes for tables now including table inverse, which you can add to create a table with a black background
2. ahead-inverse on the head, will create a table with a black header.
3. The responsive class changed a bit, you no longer have to wrap the tables with a separate div, but just add the table-responsive class directly to the table.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-table"></i> Table Colors

<ul>
	<li class="fragment"><p contenteditable>Add `table-` prefix</p>
		<small style="line-height: 220%; vertical-align: text-bottom;">
			<code style="background:#D1D1D1; color:#555;">active</code>
			<code style="background:#dff0d8; color:#555;">success</code>
			<code style="background:#d9edf7; color:#555;">info</code>
			<code style="background:#fcf8e3; color:#555;">warning</code>
			<code style="background:#f2dede; color:#555;">danger</code>
		</small>
	</li>
</ul>

>> Speaker Notes:
1. There's also a slight change with the table colors. They receive an additional prefix of table

## Conclusion
Tables is one of those features I really like about bootstrap. Styling tables can be challenging with CSS, so these styles are really awesome.