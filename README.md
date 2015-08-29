# < facebook-video />

An ember-cli component to embed facebook videos. Please note that the video must be Public. Check out [Facebook developer docs](https://developers.facebook.com/docs/plugins/embedded-video-player#add-code-manually) for more information.

## Usage

```javascript
  {{facebook-video url="https://www.facebook.com/FacebookDevelopers/videos/10152454700553553/"}}
```

And append the `<div id="fb-root"></div>` to the `body` tag

[DEMO](http://selvagsz.github.io/#/demos/fbvideo)


## Development

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
