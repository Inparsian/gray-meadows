![image](https://github.com/user-attachments/assets/8a0d11cd-6fac-4d7c-832c-12d9f463d28e)

A complete rewrite of my personal desktop suite, with a Wayland desktop shell, and soon a greetd-based greeter. Originally in TypeScript + JSX, now in Rust and a bit of C++ (for thin FFI shims).

This will probably look like a mess for a while, this is more of a personal project for me to get back into Rust development, but I'll polish things up as I go.

## Why the name "Gray Meadows"?
this uses a gray color scheme and my first screenshot of the agsv2 version used a foggy forest wallpaper. was too lazy to come up with a better name

## When will it be ready?
I have no ETA right now, but probably within a few months. This isn't a full-time project at the moment, so progress may be slow at times. Also, Rust is a fairly new language for me, so I'm still yet to get used to it's borrow checker and other quirks (I come from TypeScript lol).

Contributions are welcome!

## Building
There's no exhaustive list of dependencies at the moment, as this project is still in it's infancy. However, I can say with confidence that you will need the following:

- `libqalculate`
- `cozette-ttf` (primary font)
- `ttf-gohu-nerd` (secondary font for small & big text)
- `gtk4`
- `gtk4-layer-shell`

If I've missed any, or any of these are redundant, please open an issue or PR and I'll update this list accordingly.
