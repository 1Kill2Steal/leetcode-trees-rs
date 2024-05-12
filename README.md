# LeetCode Trees in Rust

[![Build Status]][Actions] &emsp; [![Latest Version]][crates.io]

[Build Status]: https://img.shields.io/github/actions/workflow/status/1kill2steal/leetcode-trees-rs/rust.yml?branch=main
[Actions]: https://github.com/1kill2steal/leetcode-trees-rs/actions?query=branch%3Amaster
[Latest Version]: https://img.shields.io/crates/v/leetcode-trees-rs.svg
[crates.io]: https://crates.io/crates/leetcode-trees-rs

This library is made to make any LeetCoders using Rust have a better experience
at solving their LeetCode (LC) problems. It uses cargo make to have
reproducible sub modules (check `leetcode-trees-rs/solutions/README.md`) as
well as implementing the definition of the binary trees on LC.

Quick start on using the library:

```rust
use leetcode_trees_rs::{prelude::*, utils::TreeNode}; // Importing the library.

struct Solution {} // Assigning an empty struct to make a solution impl block.

use std::{cell::RefCell, rc::Rc};
impl Solution {
    pub fn your_leetcode_fn() {}
}

fn main() -> Result<()> {
    // Your testing here . . .
    // Alternatively, you can just use functions with #[test] definitions.

    Ok(())
}
```

Additional features:

- Singly Linked Lists (example Leet - [add two numbers](https://leetcode.com/problems/add-two-numbers/description/))

- Macros (for Trees and Linked Lists)

Additional code templating can be found in [This template file](https://github.com/1Kill2Steal/leetcode-trees-rs/blob/main/solutions/lc0_general_nodes_template/src/main.rs).
It's located at: `solutions/lc0_general_nodes_template/src/main.rs`
