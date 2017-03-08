<!-- .slide: data-state="title" -->
# Bootstrap 4
Forms

>> Speaker Notes:
Bootstrap form styles make another difficult task much easier. If you're migrating forms, there's a lot of changes, so lets' take look.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Form Layout

<ul>
	<li class="fragment">No `form-horizontal`</li>
	<li class="fragment">`row` on form-groups</li>
	<li class="fragment">Different breakpoints</li>
	<li class="fragment">`input-SIZ` > `form-control-SIZ`</li>
	<li class="fragment">`col-SIZ-offset-SIZ` > `offset-BP-SIZ`</li>
</ul>

>> Speaker Notes:
1. There's some key changes to form layout, especially when it comes to horizontal forms. There is no longer a requirement to add form-horizontal to your forms.
2. However, you now have to add a row class and of course your form should have a container.
3. Remember that there are different breakpoints now, so the SM breakpoint might not be wide enough, you might have make your forms switch to an md breakpoint.
4. If you have any small or large input fields, the format for them are slightly different.
4. The way you do offsets in this version of bootstrap is also a bit different, so make sure you look for places where the old way is specified.

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Form Controls

<ul>
	<li class="fragment">`control-label` > `form-control-label`</li>
	<li class="fragment">`col-form-label`</li>
	<li class="fragment">`form-check` `form-check-label`</li>
	<li class="fragment">`form-check-inline`</li>
</ul>

>> Speaker Notes:
1. The format for the control labels are different, you add the form keyword at the beginning.
2. col-form-label if you are using a label on a column
3. There is a bit more markup in checkboxes and radio button, you'll need to add form-check and form-check-label on those type of fields.
4. if you're using inline checkboxes or radio buttons also form-check-inline

---

<!-- .slide: data-state="hasicon" -->

## <i class="fa fa-bars"></i> Aligning  Text

<ul>
	<li class="fragment"><p contenteditable>`text(-XX)-POS` align</p>
			<small style="line-height: 220%; vertical-align: text-bottom;">
				<b>XX:</b> <code style="background:#5cb85c; color:white;">sm</code> >576px 
				<code style="background:#5cb85c; color:white;">md</code> >768px 
				<code style="background:#5cb85c; color:white;">lg</code> >992px 
				<code style="background:#5cb85c; color:white;">xl</code> >1200px
			</small><br>
			<small style="line-height: 220%; vertical-align: text-bottom;"> 
				<b>POS:</b> <code style="background:#D95357; color:white;">left</code> &nbsp;
				<code style="background:#D95357; color:white;">center</code> &nbsp;
				<code style="background:#D95357; color:white;">right</code>
			</small>
	</li> 
</ul>

>> Speaker Notes:
1. Labels no longer auto align to the right, so if you want to align elements, you can just use text alignment classes.


## Conclusion
Updating forms is going to be a bit of a challenge, but once you get used to them, you'll find they're easier to work with and layout.

https://dl.dropboxusercontent.com/s/wvldr1d8pe4yikb/2017-02-12%20at%204.35%20PM.png

https://dl.dropboxusercontent.com/s/3lc8hxj7z9tgk6g/2017-02-12%20at%204.35%20PM%20%281%29.png