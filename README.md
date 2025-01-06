# Rust Raw Pointer Vector Modification Bug

This repository demonstrates a potential bug in Rust when using raw pointers to modify the contents of a vector.  Directly manipulating memory using `unsafe` code requires careful consideration of memory management and vector resizing.

The `bug.rs` file shows the unsafe code that can lead to undefined behavior.

The `bugSolution.rs` file provides a safer alternative to achieve the desired outcome without relying on unsafe operations.

**Note:** This example highlights the importance of using safe Rust practices when working with collections to avoid undefined behavior and maintain memory safety.