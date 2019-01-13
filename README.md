This crate is based off of the synchronous dark sky api crate found here: https://crates.io/crates/forecast

Everything is exactly the same except that all responses are in the form of futures that must be run/executed by your own runtime (i.e. Tokio).