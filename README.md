# ZMK Userspace

This is a repository for DHertz' zmk configuration and sheilds. See [ZMK Docs](https://zmk.dev/docs) for more information.

## Steps to complile and flash
1. Download or clone this repository
1. Run the [install steps](https://zmk.dev/docs/development/setup) for zmk, cloning the zmk repo in the same parent directory as this zmk-config repo
1. From the `app` directory of the _zmk_ repo, run `west build -b nice_nano_v2 -- -DSHIELD=the_big_switch -DZMK_CONFIG="$(pwd)/zmk-config/config" -DZMK_EXTRA_MODULES="$(pwd)/zmk-config/"` 


