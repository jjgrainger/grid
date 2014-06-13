# A Responsive CSS Grid v1.0

Another responsive CSS grid with flexible, nestable columns

* flexible, nestable columns columns
* fractional class names `.one-third`, `.two-thirds` etc
* `.push-*` classes for whitespace
* extendable, add your own classes for a feature rich grid
* uses `box-sizing: border-box`
* uses `padding` for gutters
* no `.first` or `.last` classes
* `.flow-reverse` class to change order of content on larger/small devices


## Basic usage

```html
<div class="row">
    <div class="column one-whole">
        ...
    </div>
</div>
```


## Nested Columns

```html
<div class="row">
    <div class="column one-third">
        ...
    </div>
    <div class="column two-thirds">
        <div class="row">
            <div class="column one-half">...</div>
            <div class="column one-half">...</div>
            <div class="column one-half">...</div>
            <div class="column one-half">...</div>
        </div>
    </div>
</div>
```

## Flow reverse

You can use flow reverse to display content first on mobile but appear on the right on larger screens

```html
<div class="row">
    <div class="column one-third flow-reverse">
        ...
    </div>
    <div class="column two-thirds">
        ../
    </div>
</div>
```

## Author

**Joe Grainger**

* [http://jjgrainger.co.uk](http://jjgrainger.co.uk)
* [http://twitter.com/jjgrainger](http://twitter.com/jjgrainger)