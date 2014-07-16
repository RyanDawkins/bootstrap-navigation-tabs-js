#Nav Tabs
* Author: Ryan Dawkins
* Description: This is just an extension to the Bootstrap navs page: http://getbootstrap.com/components/#nav, it was only added because
  I felt it was inconvienent to always have to recreate the javascript for the tabs.

##Example

All you need to do is add the javascript and css files and follow this simple example to get it working.

```html
<div class="nav-container">
	<ul class="nav nav-tabs nav-justified" role="tablist">
		<li class="active" data-content="#div-1">
			<a href="#">Div 1</a>
        </li>
        <li data-content="#div-2">
          	<a href="#">Div 2</a>
        </li>
    </ul>

	<div class="nav-content-container">
		<div id="div-1" class="nav-content active">
			Div 1
        </div>
        <div id="div-2" class="nav-content">
          Div 2
        </div>
	</div>
</div>
```
