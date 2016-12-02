# paginated-image-gallery

A polymer web component that shows an image-gallery component in a paginated-list component.

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

Custom property                        | Description                    | Default
---------------------------------------|--------------------------------|--------
`--paginated-image-gallery-max-height` | The max height of the gallery. | 800px


### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install
