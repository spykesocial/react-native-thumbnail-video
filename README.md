<h1>
   Custom YouTube thumbnail video with YouTube logo component
 </h1>
<p>
  Used internally to handle outbound youtube links!
</p>




## Installation

```sh
yarn add https://github.com/spykesocial/react-native-thumbnail-video
```



## Props


##### `url` (string)
URL of the video

##### `type` ([string])
Can be either `default`, `high`, `medium`, `standard` or `maximum`.

##### `imageWidth` (number/string)
Width of the image. Defaults to the device width.

##### `imageHeight` (number/string)
Height of the image. Defaults to `200`.

##### `containerStyle` ([ViewPropTypes.style](https://facebook.github.io/react-native/docs/view.html#style))
Style of the container using `TouchableOpacity`.

##### `iconStyle` ([ImagePropTypes.style](https://facebook.github.io/react-native/docs/image.html#style))
Style of the icon image.

##### `showPlayIcon` (boolean)
Show play icon. Defaults to true.

##### `onPress` (function)
Function to be called when the user presses the thumbnail. Defaults to opening the video URL.

##### `onError` (function)
Function to be called when there's an error on the default `onPress` function.

##### `children` (component)
Custom component to render inside of the thumbnail.
