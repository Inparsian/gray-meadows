⚠️ This is the legacy repository for Gray Meadows as only the shell component is being actively developed now, the git submodules will no longer be updated. Please visit the [gray-meadows-shell](https://github.com/Inparsian/gray-meadows-shell) repository instead.

![image](https://github.com/user-attachments/assets/8a0d11cd-6fac-4d7c-832c-12d9f463d28e)

A complete rewrite of my personal desktop suite, with a Wayland desktop shell, ~~and soon a greetd-based greeter~~ (see below). Originally in TypeScript + JSX, now in Rust and a bit of C++ (for thin FFI shims).

## Why the name "Gray Meadows"?
grayscale color scheme, first screenshot of the agsv2 version used a foggy forest wallpaper. was too lazy to come up with a better name

## When will it be ready?
There's no ETA right now, my initial guesstimation of within a few months was way off because I have not foreseen myself taking a break from this project for a hot minute. However, I recently started using gray-meadows-shell as a daily driver, so progress there should resume soon-ish. I have no plans to start work on the greeter in the foreseeable future.

Contributions are welcome!

## Recommended icon theme
Since Gray Meadows is intended to have a monochrome/grayscale aesthetic, I recommend you use an icon theme that matches it. My personal favorite is [Besgnulinux Monochrome](https://www.gnome-look.org/p/2151189/), but any monochrome or grayscale icon theme should work well.

## Building
There's no exhaustive list of dependencies at the moment, as this project is still in it's infancy. However, I can say with confidence that you will need the following:

- `libqalculate`
- `libadwaita` (you might already have it)
- `cozette-ttf` (primary font)
- `ttf-gohu-nerd` (secondary font for small & big text)
- `gtk4` (of course)
- `gtk4-layer-shell`
- `dart-sass` (for compiling SASS stylesheets)
- `libastal-wireplumber` (for WirePlumber support)

If I've missed any, or any of these are redundant, please open an issue or PR and I'll update this list accordingly.
