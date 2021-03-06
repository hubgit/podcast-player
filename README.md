# podcast-player

![Screenshot of podcast-player](screenshot.png)

```
<podcast-player src="my.mp3"></podcast-player>
```

A web component for audio podcasts. It has a few features that make it most suitable for podcasts:

- [x] Play/Pause
- [x] 30s Rewind Button
- [x] Seekable Progress Meter
- [x] Speed Selection
- [x] Mute/Unmute
- [x] Accessibility
- [ ] [TimeJump](http://davatron5000.github.io/TimeJump/)?

## Usage
```
bower install
```

Include `webcomponents.min.js` and `podcast-player.html` in the `<head>` of your episode page:

```
<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
<link rel="import" href="bower_components/podcast-player/elements/podcast-player.html"/>
```

Then in the body of your post, invoke the custom component using the `<podcast-player>` element.

```
<podcast-player src="my.mp3"></podcast-player>
```

BINGO-BANGO! Now you should be able to style it with good old fashioned CSS. Make it your own, good buddy.

## Testing Locally

To test out web components locally, you need to start a local server so you don't get a CORS violation with something like:

```
cd to/my/directory/
python -m SimpleHTTPServer
```

If you have questions about web components, read up on them at [webcomponents.org](http://webcomponents.org/).

## Accessibility

The Polymer core elements provide ARIA and tabIndex attributes.

There is [an open issue to fix tap event not being fired when using a keyboard](https://github.com/Polymer/polymer-gestures/issues/44).
