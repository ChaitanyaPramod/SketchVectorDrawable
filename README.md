# Export Android VectorDrawable

Exports assets as a VectorDrawable for Android. Say goodbye to a bajillion assets.

![screenshot](img/screenshot1.png)

Supports [VectorDrawable] as well as the [VectorDrawableCompat](https://medium.com/@chrisbanes/appcompat-v23-2-age-of-the-vectors-91cbafa87c88).

## Installing Plugins
### The conventional way:
1. [Download the ZIP file of master](https://github.com/ChaitanyaPramod/SketchVectorDrawable/archive/master.zip)
2. Copy the contents to the plugin folder (Open up Sketch, and go to `Plugins` › `Reveal Plugins Folder…` to open it.)

### The quickest way:

_NOTE: If your Mac has not installed GitHub client, You need to install [GitHub for mac](https://mac.github.com)_

1. Click on the [Clone in Desktop](github-mac://openRepo/https://github.com/jacobmoncur/SketchVectorDrawable) button on GitHub
2. Press `command` + `shift` + `g` to find plugin folder, then paste plugin folder path

**Plugin Folder Path**

* App Store `~/Library/Containers/com.bohemiancoding.sketch3/Data/Library/Application Support/com.bohemiancoding.sketch3/Plugins`
* Beta `~/Library/Application Support/com.bohemiancoding.sketch3/Plugins`

## Shortcuts

* Export: cmd + shift + ;

## Props to:

* [svg2android]. Svg to VectorDrawable webpage (super cool). A lot of the translation is based off this.
* [sketch-export-assets]. What I based this sketch plugin off of.

[svg2android]:https://github.com/inloop/svg2android
[sketch-export-assets]:https://github.com/geertwille/sketch-export-assets
[VectorDrawable]:https://developer.android.com/reference/android/graphics/drawable/VectorDrawable.html
