<!-- .slide: data-state="title" -->
# Bootstrap 4
Grid Changes

>> Speaker Notes: If you enjoyed using the old system of containers, rows and columns, it still exists in bootstrap, even though you can handle layout with flexbox. Migrating is going to be somewhat of a challenge, so let's take a look.

---

## Old vs New Grid

| **B3** |  Extra Small | Small | Medium | Large |
|---| :---: |:---:|:---:|:---:|
| **Break** | <768px | ≥768px | ≥992px | ≥1200px |
| **Width** | Auto | 750px | 970px | 1170px |
| **class** | .col-xs- | .col-sm- | .col-md- | .col-lg- |

| **B4** | Extra Small | Small | Medium | Large | Extra Large |
|---| :---: |:---:|:---:|:---:|
| **Break** | <576px | ≥576px | ≥768px | ≥992px | ≥1200px |
| **Width** | Auto | 540px | 720px | 940px | 1140px |
| **class** | .col- | .col-sm- | .col-md- | .col-lg- | .col-xl- |
<!-- .element: style="margin-top: 20px" -->


>> Speaker Notes:
1. Let's review the basics of the new grid using this table. First you'll notice that the new grid has an extra breakpoint at a smaller size of 576px.
2. The smallest breakpoint is no longer called XS in the grid, it's simply called col, so if you have references to an xs breakpoint, you'll have to change them to just col. The distribution of the rest of the breakpoints have changed with the largest breakpoint now called XS, but at the same size as the lg breakpoint.
3. When upgrading your layouts will shift a bit and it was really rare to use the XS breakpoint because it mean forcing your layouts to a certain amount of columns, but it's something you'll want to check out.

---

## Other Classes

<ul>
	<li class="fragment">`no-gutters` rows</li>
	<li class="fragment"><p contenteditable>`flex(-BP)-ORD`</p>
	<small style="line-height: 220%; vertical-align: text-bottom;">
		<b>BP:</b> <code style="background:#5cb85c; color:white;">sm</code> >576px 
		<code style="background:#5cb85c; color:white;">md</code> >768px 
		<code style="background:#5cb85c; color:white;">lg</code> >992px 
		<code style="background:#5cb85c; color:white;">xl</code> >1200px
		</small><br>
		<small style="line-height: 220%; vertical-align: text-bottom;"> 
		<b>ORD:</b> <code style="background:#D95357; color:white;">first</code> <code style="background:#D95357; color:white;">last</code> <code style="background:#D95357; color:white;">unordered</code> 	</small>
	</li> 
</ul>

>> Speaker Notes:
1. There's a new class that lets you delete the spacing within the columns called no-gutters.
1. Although you can  still reorganize columns using push and pull, there's a way to reorder columns using flexbox. Include the word flex, then optionally a breakpoint as well as a keyword. It's not as flexible as push and pull.

## Conclusion
If you're familiar with the old grid and want to continue to use it on your layouts, the new grid is has some slight variation, but it's easy to learn.