# FinestWebView-Firebase

## How to set up documentation.html

1. Copy the appropriate mark down code from [FinestWebView README](https://github.com/TheFinestArtist/FinestWebView-Android/blob/master/README.md).
2. Go to [Dillinger](https://dillinger.io/) to convert mark down to html.
3. Copy the converted html body part and paste at documentation.html.
4. Move `<a>` tag to wrap the title. (e.g. `<h2><a id="Getting_started_0"></a>Getting started</h2>` to `<h2><a id="Getting_started_0>Getting started</a></h2>`)
5. Add `href` attribute to add named anchor for each title. (e.g. `<h2><a id="Getting_started_0>Getting started</a></h2>` to `<h2><a id="Getting_started_0" href="#Getting_started_0">Getting started</a></h2>`)
6. Add `prettyprint` to all `<pre>` tag for code pretty. (e.g. `<pre>...</pre>` to `<pre class="prettyprint">...</pre>`)
7. Add `prettyprint` to all `<code>` tag for code pretty. (e.g. `<code>...</code>` to `<code class="prettyprint">...</code>`)
