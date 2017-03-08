<!-- .slide: data-state="title" -->
# Bootstrap 4
Upgrade Summary

>> Speaker Notes:

---

## Core Changes

<ul>
	<li class="fragment">IE10+ Support</li>
	<li class="fragment">Flexbox</li>
	<li class="fragment">Less to Sass</li>
	<li class="fragment">No optional theme</li>
</ul>

>> Speaker Notes:
1. One of the big changes in this new version is that support for Internet Explorer 8 and 9 has been dropped. It means this framework was designed to work with IE10 and above. The reason for that is that a lot of the layout structure of this version of bootstrap has been handed to flexbox.
2. Flexbox is a new set of css properties that makes it easier to layout content. This new version of Bootstrap adds flexbox classes to a lot of components. It totally changes the way the layout works in significant ways.
3. Another change is that development of Bootstrap CSS has moved from the Less language to Sass. These are both programming languages for creating CSS. If you're just using the default Bootstrap CSS, this won't have an effect on you. Sass has been more popular in recent years and so this decision makes sense. If you do want to customize your colors or breakpoints or anything else about the framework you have to know Sass in order to do so.
4. One thing that could impact you is that there is no longer an optional theme. In the previous version of bootstrap, there used to be a theme that gave you more gradients and drop shadows and those are no longer considered modern in terms of design.

---

## Typography Changes

<ul>
	<li class="fragment">`px` to `rem`</li>
	<li class="fragment">Global font size</li>
	<li class="fragment">Reboot</li>
</ul>

>> Speaker Notes:
1. A really big change is that the default measurement system has been changed from pixels to rem units. Rems are a unit of measurement that is based on the root size of the document. 
2. In the old version of bootstrap, the root size was 14 px, in this version it's back up to 16px, which is the default for most browsers. Rems are more flexible than pixels and can help you create better component based sizing.
1. Another big change is a new normalizing template called Reboot. A normalizing template makes your page work consistently accross different browsers. The new version of bootstrap uses a more opinionated version that doesn't simply normalize, but also makes some decisions about how your page looks. It means that you'll need to watch out for some changes, specially when migrating.

---

## Alignment &amp; Grid

<ul>
	<li class="fragment">More responsiveness</li>
	<li class="fragment">Smaller styles</li>
	<li class="fragment">New breakpoint</li>
	<li class="fragment">`col-xs` = `col`</li>
</ul>

>> Speaker Notes:
1. Another thing you'll notice is that there are more classes that use the responsive breakpoints, so, there are classes to help you not just use different column layouts at the different breakpoints, but also set display parameters and other spacing attributes using the different breakpoints.
1. The new version of Bootstrap is smaller and simpler. There's a few reasons for that. First, it no longer includes the glyphicons that used to come with the framework, so if you're used to those, you'll have to find a better solution.
1. There is a new breakpoint in Bootstrap, so in addition to sm, md, lg you have a breakpoint called XL for extra large sizes. But the breakpoints have shifted over, so that the XL breakpoint is the same as the old LG breakpoint. In most cases, there isn't an XS breakpoint.
1. The xs breakpoint is the default, so for example, when you create columns you simply use the col keyword instead of col-xs.

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
Here's what the old grid vs the new grid looks like and you can clearly see the differences in the grid there.

---

## New Components &amp; Changes

<ul>
	<li class="fragment">Navs &amp; others</li>
	<li class="fragment">Cards</li>
	<li class="fragment">Icons</li>
	<li class="fragment">Affix</li>
</ul>

>> Speaker Notes:
1. There aren't a lot of new components in this version of bootstrap, but the components have been heavily affected by the inclusion of flexbox, so although there isn't technically a new navigation, the navs and navbars as well as other components like the carousel heavily use flexbox.
2. One totally new component is called cards. It replaces panels, thumbnails and wells and because of the layout options and flexbox becomes a much more comprehensive layout pattern.
3. The new version of bootstrap doesn't use the icon library called Glyphicons, so if you want to add icons to your layouts, you'll need to use a different solution. If you still want to use GlyphIcons, then you can go to this URL and find
3. Finally affix has been dropped from the library. Affix was a javascript component that allowed you to make some content stick upon scroll. Instead, you can use a sticky-top class to do the same thing, but browser support isn't very good. There are always third party libraries that can take care of this, but in the future, browser support is sure to improve.


## Conclusion
Bootstrap 4 is not just a major re-write of the framework...it's a completely new rethinking of how you should lay out your pages. The rest of this course is divided into two parts. In the new few movies, we'll be discussing a lot of the new features, expecially relating to layout and display. Then, in the next chapter, we'll be looking speficically at migrating old componet to the new structure.