# paginated-image-gallery

A Polymer Element showing an image-gallery element in a paginated-list element.

### Example
```html
<paginated-image-gallery
  image-items="[[list]]"
  total-items="[[size]]"
  loading="[[loading]]"
  page="{{page}}">
</paginated-image-gallery>
```

### Styling

`<paginated-image-gallery>` provides the following custom properties and mixins for styling:

Custom property                        | Description                    | Default
---------------------------------------|--------------------------------|--------
`--paginated-image-gallery-max-height` | The max height of the gallery. | 800px


### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

