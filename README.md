# mastodon-tools
Embed [Mastodon](https://github.com/tootsuite/mastodon) statuses all around the web.

## Wordpress

Embed Mastodon statuses in you blog or whatever Wordpress site.

![Screenshot](http://mastodon.tools/wordpress/screenshot.png)


### Example

As seen at  https://blog.davidlibeau.fr/dev-test-embed-mastodon/


```
Example

[mastodon url="https://mastodon.xyz/@David/15605"][/mastodon]

https forced:
[mastodon url="https://mastodon.social/@Gargron/1"][/mastodon]

image:
[mastodon url="https://mastodon.xyz/@David/252287" height="500"][/mastodon]

spoiler:
[mastodon url="https://mastodon.xyz/@David/291091" height="250"][/mastodon]
```


## ogp-share [indev]

Share Mastodon statuses on all the other social network (Twitter, Facebook...).
Render your status in Twitter Card of Facebook with [OGP](http://ogp.me/) metatags.

```
http://share.mastodon.tools/?url=https://mastodon.xyz/@David/192108
```

### Exemple

![Screenshot Twitter](http://mastodon.tools/ogp-share/screenshots/tw.png)

![Screenshot Facebook](http://mastodon.tools/ogp-share/screenshots/fb.png)


## Dev

In dev folder, I am trying things.



[I'm @David@mastodon.xyz](https://mastodon.xyz/@David)
