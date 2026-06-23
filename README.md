# CI

This workflow just designed for the maintainers, not for the community.\
Focuses on Push/PR actions correction.

If you are meber of the Jule community and want to use GitHub Actions to test your project or etc.\
Please use the generel-driven [`julelang/setup-jule`](https://github.com/julelang/setup-jule) instead of this action.

> [!IMPORTANT]
> This CI adds the Jule compiler to the PATH by default.
> However, there is no guarantee that it will work as expected.
> You may encounter problems on some platforms.
> That's why `bin\julec` is the recommended way to use the Jule compiler.

## License

This workflow is distributed under the terms of the BSD 3-Clause license.\
[See License Details](./LICENSE)
