# native-ducks

This might become a native [Mozilla Hubs](https://hubs.mozilla.com/) client, but for now it's just a playground for Amethyst, glTF and VR.

---
*(generated readme instructions)*

---
## How to run

To run the game, use

```
cargo run --features "vulkan"
```

on Windows and Linux, and

```
cargo run --features "metal"
```

on macOS.

For building without any graphics backend, you can use

```
cargo run --features "empty"
```

but be aware that as soon as you need any rendering you won't be able to run your game when using
the `empty` feature.
