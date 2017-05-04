---
title: "selected  portfolio"
---

# Stingray hands-on training mission

These in-product tutorials are designed to accompany a new user through all the main steps of creating content in Stingray.

I designed the content, wrote the UI text, and programmed the JavaScript framework on top of an open-source module and our editor's plug-in system.

<a id="training_images" href="javascript:;"><img src="/images/marker_light_2d.png"></a>
<script>
$(document).ready( function () {
	$("a#training_images").click(
		function() {
			$.fancybox.open([
				{src:'/images/lighting_direct_only.jpg'},
				{src:'/images/lighting_combined.jpg'},
				{src:'/images/lighting_emissive_on_off.jpg'},
				{src:'/images/lighting_sky.jpg'}
				]
			);
		});
	});
</script>

To try it out, you can [install a trial](https://www.autodesk.com/products/stingray/overview) and choose **Help > Hands-on Training Mission** from the main menu.


# Stingray SDK Help

The SDK helps customers extend the Stingray environment to work with their own custom kinds of content, and integrate with third-party software.

The docs require knowledge of how Stingray works internally, and how to code in multiple languages (C/C++, JavaScript, Lua).



# Stingray Lua and visual programming reference docs

I programmed a doc build system that turns code comments into HTML. The overall styling was done to match our existing doxygen references, but I added some nice extras like the typeahead search and expanding sections.

IMAGES

The C plugin reference is extra-special. Instead of a doxygen-like system where API elements are pulled out of context and shown on their own reference pages, this is a browsable and searchable rendering of the header files. Tooltips show docs, and offer navigation between definitions and usage examples.

IMAGES


