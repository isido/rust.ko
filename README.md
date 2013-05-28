# rust.ko

a minimal kernel module written in rust.

# TL;DR

    $ make
    # insmod hello.ko
    # rmmod hello
    $ dmesg | tail -3
      [54024.186997] hello: init
      [54024.187000] hello from rust
      [54024.191963] hello: exit

    $ cat main.rs
    
# refs
 - https://github.com/pcwalton/zero.rs.git
 - https://github.com/charliesome/rustboot.git