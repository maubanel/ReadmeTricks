This is <mark>important</mark> text.


# ReadmeTricks
My favorite README formatting techniques that are both documented and undocumented.

## Video Embed:
Drag and drop .mp4 and it creates an embedded link!

https://user-images.githubusercontent.com/5504953/124366609-e3385880-dc05-11eb-9092-2f218c1ea813.mp4


## Outside link
```markdown
[DMAE Website](https://dmae.lsu.edu)
```

[DMAE Website](https://dmae.lsu.edu)


## Include Image
```markdown
![alt text](PTH.png)
```

![alt text](./PTH.png)

## New Paragraph
```markdown
If you put a space between two lines it sets them as separate

paragraphs.
```

If you put a space between two lines it sets them as separate

paragraphs.

## Inline text
```markdown
If you do not put a space between
two lines it treats it as a single paragraph.
```

If you do not put a space between
two lines it treats it as a single paragraph.

## Preserve line Breaks

Use `<pre>` tags to preverve formating

```markdown
<pre>
Words on
separate
lines, ok?
</pre>
```

<pre>
Words on
separate
lines, ok?
</pre>


## Hidden Comment

```markdown

You cannot read line 2

<!-- line 2 is not unreadable --> 

as the above line is hidden
```

You cannot read line 2

<!-- line 2 is not unreadable --> 

as the above line is hidden

## Mono Space Text
```markdown
<samp>Monospaced text</samp>
```

## Inline Code

<pre>this passworld `12345` is inline code</pre>

this passworld `12345` is inline code

## Code with spacing preserved
<pre>
```c++
int c = 10;
c++;
if (c > 11)
{
  c = 50;
}
```
</pre> 

```c++
int c = 10;
c++;
if (c > 11)
{
  c = 50;
}
```

<samp>Monospaced text</samp>

## Underline
```markdown
<ins>Underlined text</ins>
```

<ins>Underlined text</ins>



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

## Banners using svgs

```markdown
<!-- banner.svg -->
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="100" viewBox="0 0 1200 100">
  <!-- Hardcoded neon green background -->
  <rect width="1200" height="100" fill="#39FF14"/>

  <!-- Hardcoded text in black -->
  <text x="50%" y="50%" text-anchor="middle" dominant-baseline="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="36" font-weight="bold"
        fill="#000000">
    NEXT UP — README.md File
  </text>
</svg>

```

```markdown
![Next Up](svg-test.svg)
```

![Next Up](svg-test.svg)


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
| [DMAE](https://dmae.lsu.edu)|
|---|

| [DMAE](https://dmae.lsu.edu)|[DMAE](https://dmae.lsu.edu)||[DMAE](https://dmae.lsu.edu)|
|---|---|---|
```


| [Mauby](https://marcaubanel.com)|
|---|

| [Mauby](https://marcaubanel.com)|[Mauby](https://marcaubanel.com)|[Mauby](https://marcaubanel.com)|
|---|---|---|


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

## Progress Bar
```
Progress: ███████░░░░ 70%
```

Progress: ███████░░░░ 70%

## Call Outs

```markdown
> ⚠️ **Warning:** This feature is experimental!
```

> ⚠️ **Warning:** This feature is experimental!


