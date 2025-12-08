```rust
struct Dev {
    role: &'static str,
    area: &'static str,
    background: (&'static str, &'static str),
}

const ME: Dev = Dev {
    role: "startup engineer",
    area: "HPC",
    background: ("SpaceAIC", "UIUC"),
};
```
