# Running examples

If you want to run examples in any of the repos, they can be run in their own paths (otherwise
manifest path is messed up)

If you want to run things with the latest changes accross repositories, run them here but with
manifest dir set to the workspace and configure the patch there.

eg

cd utopia-planitia
cargo run --manifest-path ../Cargo.toml

where Cargo.toml patches sarekt's version to the local directory


