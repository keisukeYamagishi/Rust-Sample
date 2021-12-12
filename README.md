# Rust-Sample


## Usage

```bash
$ cargo run
```

Result

```
keisukeyamagishi~/code/r-rocket/Rust-Sample: [main]$: 
->> cargo run
    Updating crates.io index
  Downloaded libc v0.2.111
  Downloaded 1 crate (571.3 KB) in 1.11s
   Compiling version_check v0.9.3
   Compiling typenum v1.14.0
   Compiling libc v0.2.111
   Compiling cfg-if v1.0.0
   Compiling proc-macro2 v0.4.30
   Compiling yansi v0.5.0
   Compiling unicode-xid v0.1.0
   Compiling syn v0.15.44
   Compiling subtle v2.4.1
   Compiling log v0.4.14
   Compiling tinyvec_macros v0.1.0
   Compiling opaque-debug v0.3.0
   Compiling version_check v0.1.5
   Compiling unicode-bidi v0.3.7
   Compiling autocfg v1.0.1
   Compiling httparse v1.5.1
   Compiling matches v0.1.9
   Compiling percent-encoding v2.1.0
   Compiling percent-encoding v1.0.1
   Compiling byteorder v1.4.3
   Compiling cpuid-bool v0.2.0
   Compiling safemem v0.3.3
   Compiling typeable v0.1.2
   Compiling bitflags v1.3.2
   Compiling traitobject v0.1.0
   Compiling hashbrown v0.11.2
   Compiling language-tags v0.2.2
   Compiling ppv-lite86 v0.2.15
   Compiling serde v1.0.131
   Compiling state v0.4.2
   Compiling smallvec v1.7.0
   Compiling cpufeatures v0.2.1
   Compiling memchr v2.4.1
   Compiling base64 v0.13.0
   Compiling glob v0.3.0
   Compiling tinyvec v1.5.1
   Compiling generic-array v0.14.4
   Compiling pear_codegen v0.1.4
   Compiling rocket_codegen v0.4.10
   Compiling rocket v0.4.10
   Compiling unicase v1.4.2
   Compiling indexmap v1.7.0
   Compiling base64 v0.9.3
   Compiling unicode-normalization v0.1.19
   Compiling log v0.3.9
   Compiling quote v0.6.13
   Compiling mime v0.2.6
   Compiling time v0.1.43
   Compiling getrandom v0.2.3
   Compiling num_cpus v1.13.0
   Compiling atty v0.2.14
   Compiling idna v0.1.5
   Compiling rand_core v0.6.3
   Compiling cookie v0.11.4
   Compiling rand_chacha v0.3.1
   Compiling cipher v0.2.5
   Compiling universal-hash v0.4.1
   Compiling digest v0.9.0
   Compiling crypto-mac v0.10.1
   Compiling aead v0.3.2
   Compiling block-buffer v0.9.0
   Compiling rand v0.8.4
   Compiling polyval v0.4.5
   Compiling url v1.7.2
   Compiling aes-soft v0.6.4
   Compiling ctr v0.6.0
   Compiling hmac v0.10.1
   Compiling sha2 v0.9.8
   Compiling ghash v0.3.1
   Compiling aes v0.6.0
   Compiling hkdf v0.10.0
   Compiling aes-gcm v0.8.0
   Compiling hyper v0.10.16
   Compiling toml v0.4.10
   Compiling devise_core v0.2.0
   Compiling devise_codegen v0.2.0
   Compiling devise v0.2.0
   Compiling pear v0.1.4
   Compiling rocket_http v0.4.10
   Compiling hello v0.1.0 (/Users/keisukeyamagishi/code/r-rocket/Rust-Sample)
    Finished dev [unoptimized + debuginfo] target(s) in 37.46s
     Running `target/debug/hello`
🔧 Configured for development.
    => address: localhost
    => port: 8000
    => log: normal
    => workers: 16
    => secret key: generated
    => limits: forms = 32KiB
    => keep-alive: 5s
    => read timeout: 5s
    => write timeout: 5s
    => tls: disabled
🛰  Mounting /:
    => GET / (index)
🚀 Rocket has launched from http://localhost:8000
GET / text/html:
    => Matched: GET / (index)
    => Outcome: Success
    => Response succeeded.
GET /favicon.ico image/avif:
    => Error: No matching routes for GET /favicon.ico image/avif.
    => Warning: Responding with 404 Not Found catcher.
    => Response succeeded.

```
