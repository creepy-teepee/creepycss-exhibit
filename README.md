# Exhibit

The exhibit object displayed stacked media and descriptive content.

## Installation

    bower install --save creepycss-exhibit

## Usage

```
@import 'bower_components/creepycss-exhibit/objects.exhibit';
```

```
<div class="o-exhibit">
	<img src="" alt="" class="o-exhibit__media">
	<div class="o-exhibit__body">
		<h3>Heading</h3>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Repellendus ab quidem qui beatae, dolorum nam. Totam inventore excepturi, sequi voluptatibus ut consequuntur.</p>
	</div>
</div>
```

There are also tiny, small, large and huge variants that alter the spacing between media and content. These are enabled by changing the relevant flag variable and added as modifier classes, e.g. `o-exhibit--large`.