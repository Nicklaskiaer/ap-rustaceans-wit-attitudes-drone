# Rustaceans Wit Attitudes Drone
Drone for the Advanced Programming university's project.

## How to import the project
Add to your `cargo.toml` the line:
```toml
rustaceans_wit_attitudes = { git = "https://github.com/Nicklaskiaer/ap-rustaceans-wit-attitudes-drone.git" }
```
NOTE: The code may change, it's advised to run `cargo update` periodically.

## Using the drone
```rust
use rustaceans_wit_attitudes::RustaceansWitAttitudesDrone;

fn main() {
    /* ... */
    RustaceansWitAttitudesDrone::new(/* add missing arguments */);
    /* ... */
}
```

## Support
You can contact us on Telegram: https://t.me/rustaceans_wit_attitudes