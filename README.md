# paginated-image-gallery

A Polymer Element showing an image-gallery component in a paginated-list component.

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
