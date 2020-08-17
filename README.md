# wgpu-subscriber

[![Crates.io](https://img.shields.io/crates/v/wgpu-subscriber.svg?label=wgpu-subsciber)](https://crates.io/crates/wgpu-subscriber) [![docs.rs](https://docs.rs/wgpu-subscriber/badge.svg)](https://docs.rs/wgpu-subscriber/)

Easy to use tracing subscribers tuned to usage in wgpu.

`initialize_default_subscriber` will set everything up
in a default configuration.

Subscribers:
- `ChromeTracingLayer`: Output to chrome tracing format
- `FmtLayer`: Formatted output to stderr/stdout.

License: MPL-2.0
