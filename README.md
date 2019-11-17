# NAME

Devel::Cover::Report::Codecovbash - Generate a JSON file to be uploaded with the codecov bash script.

# VERSION

version 0.01

# DESCRIPTION

This is a coverage reporter for Codecov. It generates a JSON file that can be
uploaded with the bash script provided by codecov. See
[https://docs.codecov.io/docs/about-the-codecov-bash-uploader](https://docs.codecov.io/docs/about-the-codecov-bash-uploader) for details.

The generated file will be named `codecov.json` and will be in the
`cover_db` directory by default.

# UPLOADING RESULTS

Use the codecov bash script:

    cover -report codecovbash
    bash < (curl -s https://codecov.io/bash) -t token -f cover_db/codecov.json

# SUPPORT

Bugs may be submitted at [https://github.com/houseabsolute/Devel-Cover-Report-Codecovbash/issues](https://github.com/houseabsolute/Devel-Cover-Report-Codecovbash/issues).

I am also usually active on IRC as 'autarch' on `irc://irc.perl.org`.

# SOURCE

The source code repository for Devel-Cover-Report-Codecovbash can be found at [https://github.com/houseabsolute/Devel-Cover-Report-Codecovbash](https://github.com/houseabsolute/Devel-Cover-Report-Codecovbash).

# AUTHOR

Dave Rolsky <autarch@urth.org>

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2019 by Pine Mizune.

This is free software, licensed under:

    The MIT (X11) License

The full text of the license can be found in the
`LICENSE` file included with this distribution.
