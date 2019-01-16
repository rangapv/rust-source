# rust-source
Just One Command:

curl https://sh.rustup.rs -sSf | sh

That's it and follow the on-screen command

This will download and install the official compiler for the Rust programming 
language, and its package manager, Cargo.

It will add the cargo, rustc, rustup and other commands to Cargo's bin 
directory, located at:

  /home/rangapv/.cargo/bin

This path will then be added to your PATH environment variable by modifying the
profile file located at:

  /home/rangapv/.profile

You can uninstall at any time with rustup self uninstall and these changes will
be reverted.
