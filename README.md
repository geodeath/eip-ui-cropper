## uiCropper

Image Crop directive for AngularJS customised for the Particle CMS.


## Installing

#### Download directly
[Download eip-ui-cropper](https://github.com/geodeath/eip-ui-cropper)

#### Bower
	bower install eip-ui-cropper

#### NPM
	npm install eip-ui-cropper

#### Meteor
	meteor npm install --save eip-ui-cropper

## How to Use

``` javascript
angular.module('app', ['uiCropper'])
.controller(function($scope){
	$scope.myImage = 'https://raw.githubusercontent.com/CrackerakiUA/ui-cropper/master/screenshots/live.jpg';
	$scope.myCroppedImage = ''; // in this variable you will have dataUrl of cropped area.
});
```
``` html
<ui-cropper image="myImage" result-image="myCroppedImage"></ui-cropper>
```

## Documentation

You can checkout all options under [our wiki page](https://github.com/CrackerakiUA/ui-cropper/wiki/Options)