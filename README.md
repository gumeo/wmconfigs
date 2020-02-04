# wmconfigs, still work in progress...

## Personal installation

For fast reproduction of my current setup I want a simple way to install all my configurations for a slim i3 environment.

When I first started with i3, (around 2015). I did some minor stylistic configurations from some blog posts and videos I found (some ricing...). I started using vanilla Ubuntu again late 2018. Now (early 2019) I want to give i3 a try again, since I could do some things much more efficiently with i3. 

But... a vanilla i3 installation only gets you so far. There are a few features that I really want, e.g.:

1) Sound control, (Think I will add polybar for that)
2) Slack notification (Will also come from polybar)
3) Screenshot utilities (Added some bindings in config). Mostly want fast selection screenshot to clipboard.
4) Screen lock (i3lock + some imagemagic)
5) Using peek for gifs, (finally works in i3 4.17.1 by default)
6) Deal with multiple screens and presenations on an external monitor.
7) Configure some applications to open in workspaces on startup.

## Dependencies

Following will be installed:

```
i3 (minimum 4.17.1)
scrot (screenshot utility)
compton
xclip
peek
i3lock
ranger (from github)
```

I will maybe add more things later.

# TODO

1) Complete config files
2) Installation script
3) Parameters for installation, e.g. install deps or not.

## Polybar

I'm testing out polybar, just using the vanillar installation for now.I just compiled it from source and it mostly works. The only issue was symbols/glyphs not appearing. I followed the instructions on the [wiki](https://github.com/polybar/polybar/wiki/Fonts) to fix it, and installed the required fonts. Note that `polybar.sh` **has to be executable**.
