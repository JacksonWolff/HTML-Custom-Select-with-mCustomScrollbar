# HTML Custom Select with mCustomScrollbar
A very simple way to make a custom dropdown select. Using http://manos.malihu.gr jQuery Plugin to custom scrollbar.

If you are a Front-end developer like me, this is a common situation for you.

You open the PSD, start to cut the images you want, and surprise... the designer customize all the "selects", and the scrollbars :D (Thanks designers).
Tired to use another plugins, I just want to make this thing a little more fast and simple.

Using jQuery to make this, the click in a option get the attribute 'data-value' of the item and set to a hidden input to work normal inside a form tag :D.
Works with multiple custom selects.

```html
<h2>Example of code</h2>
   <div class="select-content">
		<div class="field-you-want select-oper">Select a option</div>
		<div class="dropdown-select-custom">
			<p data-value="1">Option 1</p>
			<p data-value="2">Option 2</p>
			<p data-value="3">Option 3</p>
			<p data-value="4">Option 4</p>
			<p data-value="5">Option 5</p>						
		</div>
		<input type="hidden" name="field-name" class="field-name default-input">
	</div> 
```
