# Color
<p>
<a href="https://crates.io/crates/colci" alt="colci">
<img src="https://img.shields.io/crates/v/colci" /></a>
</p>

Make ASCII color strings.

## Usage:
```rust
use colci::Color;

Color::Cyan("All tests PASSED.").make();
Color::Yellow("Congratulations!").make();
```

## Supported Colors:
- Cyan
- Green
- Red
- Yellow
- Blue
- Magenta
