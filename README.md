AWS CLI v2, in a single file
========
[AWS CLI v2] in a single file, powered by [AppImage].

```console
$ ./aws --help
usage: aws [-h] [--profile PROFILE] [--debug]

optional arguments:
  -h, --help         show this help message and exit
  --profile PROFILE
  --debug
```

NOTE: This is not an official AWS CLI v2 application. See [aws/aws-cli#4947] for
the history and drama.

Installation
--------
```bash
curl -L https://github.com/simnalamburt/awscliv2.appimage/releases/latest/download/aws-x86_64.AppImage -o aws
chmod +x aws
```

How to help
--------
- Ping AWS team to release an official AppImage distribution
- Help me setup automated build for future AWS CLI v2 releases
- Help me build binaries for the other CPU architectures, especially AArch64
- Share your experience in issues

&nbsp;

--------
*awscliv2.appimage* is primarily distributed under the terms of both the [Apache
License (Version 2.0)] and the [MIT license]. See [COPYRIGHT] for details.

[AWS CLI v2]: https://awscli.amazonaws.com/v2/documentation/api/latest/index.html
[AppImage]: https://appimage.org/
[aws/aws-cli#4947]: https://github.com/aws/aws-cli/issues/4947

[Apache License (Version 2.0)]: LICENSE-APACHE
[MIT license]: LICENSE-MIT
[COPYRIGHT]: COPYRIGHT
