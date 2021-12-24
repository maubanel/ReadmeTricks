# ReadmeTricks
My favorite README formatting techniques that are both documented and undocumented.

## Video Embed:
Drag and drop .mp4 and it creates an embedded link!

https://user-images.githubusercontent.com/5504953/124366609-e3385880-dc05-11eb-9092-2f218c1ea813.mp4


## Reusable links
```markdown
[test]: https://marcaubanel.com

Got to [mauby's website][test]
```
[test]: https://marcaubanel.com

* Got to [mauby's website][test].
* You can do the same thing with images ```[text]: link ![text]```

## Hidden Comment
* Below comment is hidden

```[//]: # (This comment will not be seen)```markdown

[//]: # (This comment will not be seen)

## Mono Space Text
```markdown
<samp>Monospaced text</samp>
```

## Underline
```markdown
<ins>Undrelined text</ins>
```

<ins>Undrelined text</ins>


<samp>Monospaced text</samp>

## Boxed Text
```markdown
<table><tr><td>Boxed text</td></tr></table>
```


<table><tr><td>Boxed text</td></tr></table>

## Pixel Perfect Gap in Text
```markdown
Huge gap follows: <img width="100"> text after huge gap
```


Huge gap follows: <img width="100"> text after huge gap

## Interesting Titles
```markdown
# `'Mauby'`|`First.Chapter`
```
# `'Mauby'`|`First.Chapter`

## Definition
```markdown
<dl>
  <dt>Term</dt>
  <dd>definition</dd>
</dl>
```


<dl>
  <dt>Term</dt>
  <dd>definition</dd>
</dl>



## Resize and position image

```markdown
<img src="https://placeholder.com/wp-content/uploads/2018/10/placeholder.com-logo1.jpg" width=100 align=left>
<img src="https://placeholder.com/wp-content/uploads/2018/10/placeholder.com-logo1.jpg" width=100 align=right>
<p align=center>
<img src="https://placeholder.com/wp-content/uploads/2018/10/placeholder.com-logo1.jpg" width=100>
</p>
```

<img src="https://placeholder.com/wp-content/uploads/2018/10/placeholder.com-logo1.jpg" width=100 align=left>
<img src="https://placeholder.com/wp-content/uploads/2018/10/placeholder.com-logo1.jpg" width=100 align=right>
<p align=center>
<img src="https://placeholder.com/wp-content/uploads/2018/10/placeholder.com-logo1.jpg" width=100>
</p>

## Color Background and Swatch using placeholder.com

```markdown
<img src="https://via.placeholder.com/150/0000FF/FFFFFF/?text=Mauby">
```

<img src="https://via.placeholder.com/150/0000FF/FFFFFF/?text=Mauby">

```
* ![#ff0000](https://via.placeholder.com/15/0000FF/0000FF) Blue!
```

* ![#ff0000](https://via.placeholder.com/15/0000FF/0000FF) Blue!

## Color Line Break using placeholder.com
`<img src="https://via.placeholder.com/1000x4/45D7CA/45D7CA" alt="drawing" height="4px"/>`<br>
<img src="https://via.placeholder.com/1000x4/45D7CA/45D7CA" alt="drawing" height="4px"/>

## Shields

[Build Shield](https://shields.io/category/size)

```markdown
![GitHub last commit](https://img.shields.io/github/last-commit/maubanel/ReadmeTricks?style=plastic)
```

![GitHub last commit](https://img.shields.io/github/last-commit/maubanel/ReadmeTricks?style=plastic)

```markdown
![GitHub repo size](https://img.shields.io/github/repo-size/maubanel/ReadmeTricks?style=plastic)
```


![GitHub repo size](https://img.shields.io/github/repo-size/maubanel/ReadmeTricks?style=plastic)


## Hide Content

```markdown
<details>
  <summary>HINT</summary>
   This is a HUGE hint!<br>
   This is a <sub>small</sub> hint!
</details>
```


<details>
  <summary>HINT</summary>
   This is a HUGE hint!<br>
   This is a <sub>small</sub> hint!
</details>

## Button using Tables
```markdown
| [Mauby](https://marcaubanel.com)|
|---|

| [Mauby](https://marcaubanel.com)|[Mauby](https://marcaubanel.com)|[Mauby](https://marcaubanel.com)|
|---|---|---|
```


| [Mauby](https://marcaubanel.com)|
|---|

| [Mauby](https://marcaubanel.com)|[Mauby](https://marcaubanel.com)|[Mauby](https://marcaubanel.com)|
|---|---|---|


<button class="button-save large">Big Fat Button</button>

## Anchor link
```markdown
[Go to Top of Page](#video-embed)
```


[Go to Top of Page](#video-embed)

## Horizontal Line

```markdown
---
```


---

## Combined Format
```markdown
* Italic-bold -> __*Mauby*__
* superscript -italic -> Mauby<sup>*tm*</sup>
* italic-bold-strikethrough -> ~~__*Cancelled*__~~
```


* Italic-bold -> __*Mauby*__
* superscript -italic -> Mauby<sup>*tm*</sup>
* italic-bold-strikethrough -> ~~__*Cancelled*__~~

## Stringed Together Links
```
[Website](http://www.serverless.com) • [Email Updates](http://eepurl.com/b8dv4P) • [Gitter](https://gitter.im/serverless/serverless) • [Forum](http://forum.serverless.com) • [Meetups](https://github.com/serverless-meetups/main) • [Twitter](https://twitter.com/goserverless) • [Facebook](https://www.facebook.com/serverless) • [Contact Us](mailto:hello@serverless.com)```
```

[Website](http://www.serverless.com) • [Email Updates](http://eepurl.com/b8dv4P) • [Gitter](https://gitter.im/serverless/serverless) • [Forum](http://forum.serverless.com) • [Meetups](https://github.com/serverless-meetups/main) • [Twitter](https://twitter.com/goserverless) • [Facebook](https://www.facebook.com/serverless) • [Contact Us](mailto:hello@serverless.com)

## Syntax Highlighting
````
```javascript 
function fancyAlert(arg) {
  if(arg) {
  $.facebox({div:'#foo'})
  }
}
```
````


```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Tasklist
```markdown
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item``
```

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Emojis
`:exclamation:`<br>
Get all at https://www.webfx.com/tools/emoji-cheat-sheet/* 
* :exclamation:
* :musical_note:
* :speech_balloon:
* :thought_balloon:
* :busts_in_silhouette:
* :cop:
* :angel:
* :point_up_2:
* :clap:
* :muscle:
* :raised_hands:
* :point_right:
* :point_left:
* :point_down:
* :ok_hand:
* :raised_hand:
* :+1:
* :-1:
* :fire:
* :question:
* :anger:
* :boom:
* :sparkles:
* :heart:
* :blue_heart:
* :yellow_heart:
* :purple_heart:
* :broken_heart:
* :sunglasses:
* :mask:
* :innocent:
* :triumph:
* :rage:
* :joy:
* :sleeping:
* :worried:
* :open_mouth:
* :grinning:
* :wink:
* :smirk:
* :cloud:
* :beetle:
* :bell:
* :tada:
* :floppy_disk:
* :movie_camera:
* :speaker:
* :speaker:
* :mag_right:
* :postbox:
* :nut_and_bolt:
* :open_file_folder:
* :paperclip:
* :notebook:
* :video_game:
* :clapper:
* :dart:
* :trophy:
* :triangular_ruler:
* :flashlight:
* :hourglass:
* :computer:
* :key:
* :wrench:
* :pushpin:
* :space_invader:
* :link:
* :white_check_mark:
* :black_circle:
* :white_circle:
* :red_circle:
* :large_blue_circle:
* :large_blue_diamond:
* :small_orange_diamond:
* 🖱️

## Keyboard Markup
```markdown
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>
```


<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Space</kbd>

term
: definition


## Visualizing Diff
````
```diff
10 PRINT “BASIC IS COOL”
- 20 GOTO 11
+ 20 GOTO 10
```
````

```diff
10 PRINT “BASIC IS COOL”
- 20 GOTO 11
+ 20 GOTO 10
```

