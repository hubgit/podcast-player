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

To get started, you'll need a copy of `webcomponents.js`. Either [link from CDNjs](https://cdnjs.com/libraries/webcomponentsjs) or

```
bower install webcomponentsjs
```

Include `webcomponents.min.js` and `podcast-player.html` in the `<head>` of your episode page:

```
<script src="webcomponents.min.js"></script>
<link rel="import" href="podcast-player.html"/>
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

## Download, Fork, Commit
If you like to contribue, please feel free to fork the repo. If you created a brand new feature, I recommend discussing it in an issue first rather wasting your whole weekend working on it, then Hail Mary'ing it my way.

If you're reporting a bug, you'd better have an editable reduced test case on a CodePen or GTFO. Sorry, thems the brakes. I got kids.
