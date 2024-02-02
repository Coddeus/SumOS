# SumOS

![SumOS logo](./logo.png)
Some OS with a sumos sum logo.

At the very beginning.  
Follows the [blog of Philipp Oppermann](https://os.phil-opp.com/)

* Build: `cargo build`
* Run (requires Qemu): `cargo run`
* Send to truncated D: drive (to boot with this OS): `dd if=target/x86_64-sumos/debug/bootimage-sumos.bin of=\\.\PHYSICALDRIVE1 && sync`