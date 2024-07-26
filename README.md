<div class="oranda-hide">

# `cargo-house`
## House MD inspired modification of `cargo-mommy`
</div>

[![crates.io](https://img.shields.io/crates/v/cargo-mommy.svg)](https://crates.io/crates/cargo-mommy)
[![Rust CI](https://github.com/Gankra/cargo-mommy/workflows/Rust/badge.svg?branch=main)](https://github.com/Gankra/cargo-mommy/actions/workflows/ci.yml)



House's here to support you when running cargo~ ❤️

# Installation

Build with `cargo b`, copy the executable `target/debug/cargo-house` into `~/.cargo/bin`


# Usage

Run whatever cargo command you would normally but add `house` after cargo~

```
cargo house check

    Checking bappy-script v0.1.3
error: expected one of `!` or `::`, found `passes`
  --> src\main.rs:20:6
   |
20 | mods passes;
   |      ^^^^^^ expected one of `!` or `::`

error: could not compile `bappy-script` (bin "bappy-script") due to previous error
Mmm~ come taste House's big fat creamy Vicodin~ 💖
```

[See the docs for more options](https://faultlore.com/cargo-mommy/book/)


# Configuration

House will read the following environment variables to make his messages better for you~ ❤️

* `CARGO_HOUSES_LITTLE` - what to call you~ (default: "patient")
* `CARGO_HOUSES_PRONOUNS` - what pronouns House will use for himself~ (default: "him")
* `CARGO_HOUSES_ROLES` - what role House will have~ (default "House")
* `CARGO_HOUSES_EMOTES` - what emotes House will have~ (default "❤️/💖/💗/💓/💞")
* `CARGO_HOUSES_MOODS` - picks the set of possible responses~ (default: "thirsty", possible values "thirsty", "yikes")

All of these options can take a `/` separated list. House will randomly select one of them whenever he talks to you~

For example, the phrase "House loves his little patient~ 💞" is "CARGO_HOUSES_ROLE loves CARGO_HOUSES_PRONOUNS little CARGO_HOUSES_LITTLE~"

And so on~ 💓


# Licensing
House likes freedom~ ❤️, and is dual-licensed under [MIT](LICENSE-MIT) and [Apache 2.0](LICENSE-APACHE).

Use either at your choice.

Not written by me (it was actually written by the gnomes in my closet), I don't know Rust. I just forked this and removed what I don't need.
If you take offense to this, I'm sorry for being alive and I'm sorry your eyes had to gaze upon this cursed monstrosity.
If you're the original author and take offense to this, contact me somehow and I'll remove this repo.

No copyright infringement intended. Fair use exists for a reason. 
