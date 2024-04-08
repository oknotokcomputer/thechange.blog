---
title: Introducing okstd
date: "2024-04-08"
description: 
---

okStd is a standard library abstraction for rust that makes it easier to abstract away the differences between the various standard libraries that are available in the rust ecosystem.

```rust
use okstd::prelude::*;

// This should give you Future and Executor abstractions for tokio, async-std, smol, and cros_async
```