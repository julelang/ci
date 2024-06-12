# CI

This workflow just designed for the developers, not for the community.\
Focuses on Push/PR actions correction.

If you are meber of the Jule community and want to use GitHub Actions to test your project or etc.\
Please use the generel-driven [Panquesito7/setup-jule](https://github.com/Panquesito7/setup-jule) instead of this action.

> [!IMPORTANT]
> This CI adds the Jule compiler to the PATH by default.
> However, there is no guarantee that it will work as expected.
> You may encounter problems on some platforms.
> That's why `bin\julec` is recommended to use the Jule compiler.

## License

The reference compiler, API, and standard library are distributed under the terms of the BSD 3-Clause license.\
[See License Details](./LICENSE)
