# emoteJAM

`emoteJAM` is a simple website that generates animated [BTTV](https://betterttv.com/) emotes from static images.

That idea is to apply a well established "meme meta filters" to static emotes. Such as [JAM](https://betterttv.com/emotes/5b77ac3af7bddc567b1d5fb2), [Hop](https://betterttv.com/emotes/5a9578d6dcf3205f57ba294f), etc.

The most important feature of the website is that it's completely client-side and can be easily deployed to something like [GitHub Pages](https://pages.github.com/). It uses [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) to animate static images and [gif.js](https://jnordberg.github.io/gif.js/) to generate actual GIF files inside of your browser.

Official Deployed Instance: [https://tsoding.org/emoteJAM/](https://tsoding.org/emoteJAM/)

## Running Locally

Nothing particularly special is required. Just serve the folder using HTTP server like Python's SimpleHTTPServer:

```console
$ python -m SimpleHTTPServer 6969
$ iexplore.exe http://localhost:6969/
```
