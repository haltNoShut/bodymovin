## V 4.10.0
- Lots of new expressions
- Ouroboros 2.0 support! (in beta just in case)
- AVD Format export!

## V 4.9.0
- Full repeaters support
- Keyframes interpolation fix for stretched layers
- inBrowser method added 

## V 4.8.0
- Fonts fix for Lottie compatibility
- fonts reduced exported filesize
- fonts fix for non-zero width character
- expressions transform separate dimensions fix
- expression shape rectangle size support

## V 4.7.1
- still images validation fix
- expression for transform on separate dimensions fix

## V 4.7.0
- hiding elements when opacity is at 0
- colinear points fix
- anchor point expression fix
- server side rendering window object validation (thanks @zephinzer)

## V 4.6.11
- Non spatial interpolation fix
- new expressions supported
- fonts fix

## V 4.6.10
- AE language export fix
- nearestKey expression fix

## V 4.6.9
- new expressions. More Rubberhose support
- expression fixes
- expression sandboxing window and document
- pointInLine 3d fix

## V 4.6.8
- 3d camera fix
- fix for tests

## V 4.6.7
- Trim path with Rectangle fix

## V 4.6.6
- Text baseline supported (from After Effects 13.6 (CC 2015))
- text animator fixes

## V 4.6.5
- trim path full fix

## V 4.6.4
- velocityAtTime expression fix

## V 4.6.3
- bodymovin_light fix
- rubberhose autoflop patch for inactive admin property

## V 4.6.2
- repeaters! (partially but should cover many cases)
- new expressions
- render improvements
- reduced garbage collection

## V 4.6.1
- 3D orientation fix
- render improvements

## V 4.6.0
- New UI!
- Drop shadow effect support
- performance improvement on animations with offsetted layers
- big performance improvement on expressions
- expressions expressions expressions

## V 4.5.9
- expressions variable declaration fix
- effect control type fix

## V 4.5.8
- fill-rule for fills and gradient fills on shapes
- rounding colors values with an extra decimal
- property expressions that return strings are evaluated as numbers

## V 4.5.7
- standalone autoplay fix

## V 4.5.6
- expression instance fix for CEP
- new variables declarations in expression conditional statements
- reduced filesize on exported shapes with different vertex count
- setting parents context when calling destroy (fixes webpack issue)

## V 4.5.5
- Text selector Triangle fix
- Expressions support for "active" property on effects
- Rearranged exporting properties
- Included "a" property for animated props
- Docs updated

## V 4.5.4
- Trim path individually supported
- bug fix that messed with webpack build

## V 4.5.3
- Skipping non breaking space on characters
- levels effect optimizations
- shape expressions transform properties added (Needed to fix a Rubberhose 2 issue)
- transform properties in expression through transformInterface

## V 4.5.2
- Comp expression interface default return
- HTML renderer validation fix

## V 4.5.1
- Trim path fix
- Html renderer fixes

## V 4.5.0
- Tritone effect supported
- Levels effect supported. The one called "Levels (Individual Controls)"

## V 4.4.30
- Gradient Fill default value breaking render fix
- Demo file fix when json is renamed

## V 4.4.29
- Trim path fix
- html renderer fixes

## V 4.4.28
- expressions: better seeded random, properties by matchName, normalize support
- single shape text with keyframes fix
- masked track matted comps fix
- trim path 0% to 100% fix

## V 4.4.27
- playSegments fix
- inverting alphas with color matrices

## V 4.4.26
- expressions Math.abs fix
- Layer Index expression support
- Nested group effects fix

## V 4.4.25
- text properties matched by matchName
- destroy anims fix for animation count
- checking callbacks array before dispatching event

## V 4.4.24
- text mask path fixes
- text tracking fix on texts without animators
- transform yPosition and xPosition expression interface
- rounded corners expression interface
- shape hold keyframes last frame fix
- mask with single vertex fix
- reversed shapes on hold keyframes fix
- shape interfaces fixes
- fromWorld and toWorld expression support
- function invoked from function expression support
- inner grouped shapes transformation fix
- opacity on masks supported for svg renderer
- duplicate ellipse export fix
- rounded corners on rectangle shapes fix
- rounded corners multiple shapes fix
- time remapped stretched layers fix
- shapes with no vertices fix
- more stroke effect types support
- luminance mask fix
- alpha mask support IE and Edge

## V 4.4.23
- expressions transform opacity interface
- removing rAF when idle (thanks to @mpeterson2 for the suggestion and PR)

## V 4.4.22
- text layer defaulting line height value when first char is new line

## V 4.4.21
- stroke effect improvement

## V 4.4.20
- previous versions masks fix

## V 4.4.19
- getValueAtTime expression fix
- shape and mask expression support
- open and close shapes support per keyframe
- html renderer cyclic fix

## V 4.4.18
- standalone export fix

## V 4.4.17
- expression support for effect and effect group match name

## V 4.4.16
- support for text source keyframes
- fix parented masked layers
- new expressions
- rect shape expressions interface

## V 4.4.15
- new expressions
- blend mode fix

## V 4.4.14
- fixed bodymovin_light
- fixed translations with same origin and destination

## V 4.4.13
- preserveAspectRatio all values for canvas
- Different vertices between keyframes supported
- New expressions
- First effects: Stroke, Fill, Tint.
- Orient along path

## V 4.4.12
- Trim path fix on offsetted shapes

## V 4.4.11
- html and canvas renderer fixes
- more expressions supported
- better subtracted mask support on the svg renderer
- trim paths memory management corrected. If you're using Trim paths with animated strokes please update to this build!

## V 4.4.10
- fix on canvas nested compositions if only element animated was a mask

## V 4.4.9
- included preserveAspectRatio for canvas 'xMidYMid' and 'none' supported for now

## V 4.4.8
- animation new method "setSubframe" to enable subframe rendering (true by default).
- hidden guided layers and parenting restore
- split animations export resetting segments

## V 4.4.7
- Performance improvement
- Stroke gradient support

## V 4.4.6
- Nested gradient fix

## V 4.4.5
- Alpha masks fix

## V 4.4.4
- performance improvement on redrawing svg

## V 4.4.3
- gradient fixes
- transparency fixes
- more fixes
- assetsPath param to set where to look for assets

## V 4.4.2
- shape color interpolation fix

## V 4.4.1
- hold keyframes fix

## V 4.4.0
- Gradients! for svg and html renderer
- hidden track matte layers fix
- shape stroke performance and fix improvements

## V 4.3.3
- Hidden layer and Guided layers are now exportable if configured (could be needed for expressions)
- Config is remembered
- Filter for Comps
- Trim path fix
- Canvas images fix

## V 4.3.2
- preserveAspectRatio editable

## V 4.3.1
- Expression frameDuration property added
- shape last hold keyframe fix

## V 4.2.3
- Expressions framesToTime and timeToFrames
- Layer stretching. Negative values not supported yet.
- Firefox canvas save/restore performance fix
- Blend Modes (read blend modes page for specifications here https://github.com/bodymovin/bodymovin/wiki/Blend-Modes)

## V 4.2.2
- Compatibility fix for colors

## V 4.2.1
- Expressions fix for AE 2015.3
- Added bodymovin_light.js

## V 4.2.0
- More expressions support
- Rounded corners supported on shapes
- added goToAndPlay
- Fixes

## V 4.1.8
- Fixed easing bezier values for dimensional properties

## V 4.1.7
- removing non ASCII chars from file that would break the extension in some languages.

## V 4.1.6
- module definition fix

## V 4.1.5
- stroke transform fix

## V 4.1.4
- last hold keyframe fix

## V 4.1.3
- Unary expressions
- svg compositions opacity fix
- data-bm-renderer tag fix
- evaluating expression slider values before returning

## V 4.1.1
- UMD fix

## V 4.1.0
- UMD compatible
- more expressions
- improved bezier interpolation
- fixes

## V 4.0.10
- miter join trim fix

## V 4.0.9
- html renderer shape fix

## V 4.0.7
- some expression fixes
- trimmed closed shapes fix

## V 4.0.5
- more expressions supported
- miter closed shapes fix
- demo.html can be exported from AE for local playback
- Snapshot button renamed to Preview

## V 4.0.1
- separate dimensions fix

## V 4.0.0
- 3d
- expressions
- text
- star shape

## V 3.1.7:
- Fix rounded rects

## V 3.1.5:
- Fix AE 13.6

## V 3.1.4:
- svg transform bug fix

## V 3.1.3: Naming convention
- if you name your AE layers with a '#' in front, they will get their id attribute set to that name on the svg renderer. You can use it to add interaction to specific shapes or add additional styles.

## V 3.1.2:
- shape hold keyframe fix
- snapshot feature fix

## V 3.1.1:
- translation bug fix

## V 3.1.0: the big refactor
- reduced filesize
- increased performance
- improved memory management
- fixed scaled strokes on canvas
- events

## V 3.0.8
- changed masks to clipping paths when only using AE additive masks. Performance improvement and fixes issue with strokes.

## V 3.0.7
- rounded rects fix
- stroke dash export fix

## V 3.0.5
- major memory management optimizations. and more to come.
- big performance improvements for svg animations
- segments fixes
- devicePixelRatio support. contribution from @snorpey

## V 3.0.3
- nested strokes and shapes fix
- reverse rectangles fix
- mask fix
- reversed non closed shapes fix

## V 3.0.2
- bug fix for rounded rectangles
- default quality settings modified

## V 3.0.0
- bodymovin.setQuality to optimize player performance. explained below.
- segments: export animation in segments. more below.
- snapshot: take an svg snapshot of the animation to use as poster. more below.

## Installing extensions: Until I find a way to upload it to the Adobe Exchange store, there are two possible ways to install it.

### Option 1:

- Close After Effects<br/>
- Extract the zipped file on build/extension/bodymovin.zip to the adobe CEP folder:<br/>
WINDOWS:<br/>
C:\Program Files (x86)\Common Files\Adobe\CEP\extensions or<br/>
C:\<username>\AppData\Roaming\Adobe\CEP\extensions<br/>
MAC:<br/>
/Library/Application\ Support/Adobe/CEP/extensions/bodymovin<br/>
(you can open the terminal and type:<br/>
cp -R YOURUNZIPEDFOLDERPATH/extension /Library/Application\ Support/Adobe/CEP/extensions/bodymovin<br/>
then type:<br/>
ls /Library/Application\ Support/Adobe/CEP/extensions/bodymovin<br/>
to make sure it was copied correctly type)<br/>

- Edit the registry key:<br/>
WINDOWS:<br/>
open the registry key HKEY_CURRENT_USER/Software/Adobe/CSXS.6 and add a key named PlayerDebugMode, of type String, and value 1.<br/>
MAC:<br/>
open the file ~/Library/Preferences/com.adobe.CSXS.6.plist and add a row with key PlayerDebugMode, of type String, and value 1.<br/>

### Option 2:

Install the zxp manually following the instructions here:
https://helpx.adobe.com/x-productkb/global/installingextensionsandaddons.html  
Jump directly to "Install third-party extensions"


### For both
- Go to Edit > Preferences > General > and check on "Allow Scripts to Write Files and Access Network"

## How it works
### After Effects
- Open your AE project and select the bodymovin extension on Window > Extensions > bodymovin
- A Panel will open with a Compositions tab.
- On the Compositions tab, click Refresh to get a list of all you project Comps.
- Select the composition you want to export
- Select Destination Folder
- Click Render
- look for the exported json file (if you had images or AI layers on your animation, there will be an images folder with the exported files)

#### Settings:
**segments:** export animation in segments. If you have a main comp with more than one layer you can export the animation in parts so you won't load all at once. The exporter will segment your main comp considering where a layer starts in time.<br/>
**snapshot:** take an svg snapshot of the animation to use as poster. After you render your animation, you can take a snapshot of any frame in the animation and save it to your disk. I recommend to pass the svg through an svg optimizer like https://jakearchibald.github.io/svgomg/ and play aroud with their settings.<br/>

### HTML
- get the bodymovin.js file from the build/player/ folder for the latest build
- include the .js file on your html (remember to gzip it for production)
```
<script src="js/bodymovin.js" type="text/javascript"></script>
```
You can call bodymovin.loadAnimation() to start an animation.
It takes an object as a unique param with:
- animationData: an Object with the exported animation data.
- path: the relative path to the animation object. (animationData and path are exclusive)
- loop: true / false / number
- autoplay: true / false it will start playing as soon as it is ready
- name: animation name for future reference
- animType: 'svg' / 'canvas' to set the renderer
- prerender: true / false to prerender all animation before starting (true recommended)
<br />
Returns the animation object you can control with play, pause, setSpeed, etc.
```
bodymovin.loadAnimation({
  wrapper: element, // the dom element
  animType: 'svg',
  loop: true,
  autoplay: true,
  animationData: JSON.parse(animationData) // the animation data
});
```
- if you want to use an existing canvas to draw, you can pass an extra object: 'renderer' with the following configuration:
```
bodymovin.loadAnimation({
  wrapper: element, // the dom element
  animType: 'svg',
  loop: true,
  autoplay: true,
  animationData: animationData, // the animation data
  renderer: {
    context: canvasContext, // the canvas context
    scaleMode: 'noScale',
    clearCanvas: false
  }
});
```
If you do this, you will have to handle the canvas clearing after each frame
<br/>
Another way to load animations is adding specific attributes to a dom element.
You have to include a div and set it's class to bodymovin.
If you do it before page load, it will automatically search for all tags with the class "bodymovin".
Or you can call bodymovin.searchAnimations() after page load and it will search all elements with the class "bodymovin".
<br/>
- add the data.json to a folder relative to the html
- create a div that will contain the animation.
<br/>
 **Required**
 <br/>
 . a class called "bodymovin"
 . a "data-animation-path" attribute with relative path to the data.json
 <br/>
**Optional**
<br/>
 . a "data-anim-loop" attribute
 . a "data-name" attribute to specify a name to target play controls specifically
 <br/>
 **Example**
 <br/>
 ```
<div style="width:1067px;height:600px" class="bodymovin" data-animation-path="animation/" data-anim-loop="true" data-name="ninja"></div>
```
<br/>

## Usage
bodymovin has 8 main methods:
**bodymovin.play()** -- with 1 optional parameter **name** to target a specific animation <br/>
**bodymovin.stop()** -- with 1 optional parameter **name** to target a specific animation <br/>
**bodymovin.setSpeed()** -- first param speed (1 is normal speed) -- with 1 optional parameter **name** to target a specific animation <br/>
**bodymovin.setDirection()** -- first param direction (1 is normal direction.) -- with 1 optional parameter **name** to target a specific animation <br/>
**bodymovin.searchAnimations()** -- looks for elements with class "bodymovin" <br/>
**bodymovin.loadAnimation()** -- Explained above. returns an animation instance to control individually. <br/>
**bodymovin.destroy()** -- you can register an element directly with registerAnimation. It must have the "data-animation-path" attribute pointing at the data.json url<br />
**bodymovin.setQuality()** -- default 'high', set 'high','medium','low', or a number > 1 to improve player performance. In some animations as low as 2 won't show any difference.<br />

## Events
- onComplete
- onLoopComplete
- onEnterFrame
- onSegmentStart

you can also use addEventListener with the following events:
- complete
- loopComplete
- enterFrame
- segmentStart


See the demo folders for examples or go to http://codepen.io/airnan/ to see some cool animations

## Alerts!

### Files
If you have any images or AI layers that you haven't converted to shapes (I recommend that you convert them, so they get exported as vectors, right click each layer and do: "Create shapes from Vector Layers"), they will be saved to an images folder relative to the destination json folder.
Beware not to overwrite an exiting folder on that same location.


### Performance
This is real time rendering. Although it is pretty optimized, it always helps if you keep your AE project to what is necessary<br/>
More optimizations are on their way, but try not to use huge shapes in AE only to mask a small part of it.<br/>
Too many nodes will also affect performance.

### Help
If you have any animations that don't work or want me to export them, don't hesitate to write. <br/>
I'm really interested in seeing what kind of problems the plugin has. <br/>
my email is **hernantorrisi@gmail.com**

### Version
This is version 2.1. It is even more stable but let me know if anything comes up.

## Examples
http://codepen.io/collection/nVYWZR/ <br/>

## Support
- The script supports precomps, shapes, solids, images, null objects,
- Text, image sequences, videos and audio are not supported (maybe some of them coming soon)
- It supports masks and inverted masks. Maybe other modes will come but it has a huge performance hit.
- It supports time remapping (yeah!)
- The script supports shapes, rectangles and ellipses. It doesn't support stars yet.
- No effects whatsoever. (stroke is on it's way)
- No expressions (maybe some coming)
- **No layer stretching**! No idea why, but stretching a layer messes with all the data.

## Notes
- If you want to modify the parser or the player, there are some gulp commands that can simplify the task
- look at the great animations exported on the demo folder
- gzipping the animation jsons and the player have a huge impact on the filesize. I recommend doing it if you use it for a project.

## Coming up
- Text
- Exporting images in a sprite
- Stroke Effect support
- Experimenting with the webAnimationAPI export
- Exporting 3D animations (not vectors because there is no 3d svg support on browsers)
