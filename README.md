# ti-ionic-segmented-control
Ionic iOS segmented control.
Feel free to contribute to this project.

## How to use it
```
$ bower install ti-segmented-control
```
Include "bower_components/ti-segmented-control/dist/ti-segmented-control.js" in your project.

```
angular.module('App', ['ti-segmented-control']);
```

```html
<ti-segmented-control on-select="buttonClicked($index)" style="width: 200px;">
    <ti-segmented-control-button class="button-positive" title="'Month'"></ti-segmented-control-button>
    <ti-segmented-control-button class="button-positive" title="'Day'" selected></ti-segmented-control-button>
</ti-segmented-control>
```

## Demo
http://plnkr.co/edit/sRKNKhQbw58nGgp7YfZy?p=preview

## LICENSE
ti-ionic-segmented-control is licensed under the MIT Open Source license. For more information, see the LICENSE file in this repository.
