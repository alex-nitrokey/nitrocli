Unreleased
----------
- Show PIN related errors through `pinentry` native reporting mechanism
  instead of emitting them to `stdout`
- Applied a couple of `clippy` reported suggestions
- Changed dependency version requirements to be less strict (only up to
  the minor version and not the patch level)
- Bumped `pkg-config` dependency to `0.3.14`
- Bumped `libc` dependency to `0.2.45`
- Bumped `cc` dependency to `1.0.25`


0.1.2
-----
- Replaced deprecated `gcc` dependency with `cc` and bumped to `1.0.4`
- Bumped `hid` dependency to `0.4.1`
- Bumped `hidapi-sys` dependency to `0.1.4`
- Bumped `libc` dependency to `0.2.36`


0.1.1
-----
- Fixed display of firmware version for `status` command
- Removed workaround for incorrect CRC checksum produced by the Nitrokey
  Storage device
  - The problem has been fixed upstream (`nitrokey-storage-firmware`
    [issue #32](https://github.com/Nitrokey/nitrokey-storage-firmware/issues/32))
  - In order to be usable, a minimum firmware version of 0.47 is required


0.1.0
-----
- Initial release