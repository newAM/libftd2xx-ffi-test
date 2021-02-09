Output of `cargo build --verbose`

## Linux

```
   Compiling libftd2xx-ffi v0.5.1 (https://github.com/Grinkers/libftd2xx-ffi-rs.git?branch=main#45e99b6c)
   Compiling cfg-if v1.0.0
     Running `rustc --crate-name build_script_build --edition=2018 /home/alex/.cargo/git/checkouts/libftd2xx-ffi-rs-eebfc96ea2f692e1/45e99b6/build.rs --error-format=json --json=diagnostic-rendered-ansi --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg 'feature="static"' -C metadata=cbb6cd26198fc3ec -C extra-filename=-cbb6cd26198fc3ec --out-dir /home/alex/git/libftd2xx-ffi-test/target/debug/build/libftd2xx-ffi-cbb6cd26198fc3ec -L dependency=/home/alex/git/libftd2xx-ffi-test/target/debug/deps --cap-lints allow`
     Running `rustc --crate-name cfg_if --edition=2018 /home/alex/.cargo/registry/src/github.com-1ecc6299db9ec823/cfg-if-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 -C metadata=d836a7202f0431f0 -C extra-filename=-d836a7202f0431f0 --out-dir /home/alex/git/libftd2xx-ffi-test/target/debug/deps -L dependency=/home/alex/git/libftd2xx-ffi-test/target/debug/deps --cap-lints allow`
     Running `/home/alex/git/libftd2xx-ffi-test/target/debug/build/libftd2xx-ffi-cbb6cd26198fc3ec/build-script-build`
     Running `rustc --crate-name libftd2xx_ffi --edition=2018 /home/alex/.cargo/git/checkouts/libftd2xx-ffi-rs-eebfc96ea2f692e1/45e99b6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg 'feature="static"' -C metadata=ec113d69c8232eeb -C extra-filename=-ec113d69c8232eeb --out-dir /home/alex/git/libftd2xx-ffi-test/target/debug/deps -L dependency=/home/alex/git/libftd2xx-ffi-test/target/debug/deps --extern cfg_if=/home/alex/git/libftd2xx-ffi-test/target/debug/deps/libcfg_if-d836a7202f0431f0.rmeta --cap-lints allow -L native=/home/alex/.cargo/git/checkouts/libftd2xx-ffi-rs-eebfc96ea2f692e1/45e99b6/vendor/linux/x64/build -l static=ftd2xx`
   Compiling libftd2xx-ffi-test v0.1.0 (/home/alex/git/libftd2xx-ffi-test)
     Running `rustc --crate-name libftd2xx_ffi_test --edition=2018 src/main.rs --error-format=json --json=diagnostic-rendered-ansi --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 -C metadata=3f6485b4f49c14c3 -C extra-filename=-3f6485b4f49c14c3 --out-dir /home/alex/git/libftd2xx-ffi-test/target/debug/deps -C incremental=/home/alex/git/libftd2xx-ffi-test/target/debug/incremental -L dependency=/home/alex/git/libftd2xx-ffi-test/target/debug/deps --extern libftd2xx_ffi=/home/alex/git/libftd2xx-ffi-test/target/debug/deps/liblibftd2xx_ffi-ec113d69c8232eeb.rlib -L native=/home/alex/.cargo/git/checkouts/libftd2xx-ffi-rs-eebfc96ea2f692e1/45e99b6/vendor/linux/x64/build`
    Finished dev [unoptimized + debuginfo] target(s) in 0.71s
```

## Windows

```

```
