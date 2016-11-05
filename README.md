# atomun-docker-build

[![license](https://img.shields.io/github/license/harningt/atomun-docker-build.svg)][MIT]

Enter [Atomun](https://github.com/harningt/atomun) - the Java Bitcoin utility library collection.

This repository contains docker setup information to create builds of Atomun components.

[![Join the chat at https://gitter.im/harningt/atomun](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/harningt/atomun?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Versioning

This module will follow the guidelines set forth in [Semantic Versioning 2.0][SemVer2.0]

## License

This library is covered under the [MIT license][MIT] as indicated in the LICENSE file.

## Repository Details

The repository is managed using the Gitflow workflow. Note that any published
feature/\* branches are subject to history modification, so beware working
off of those.

Signed and annotated tags will be added in the form vMAJOR.MINOR.MICRO to denote
releases.

## Docker Build Output

Images will be provided via automated docker builds, with information viewable at:

https://hub.docker.com/r/harningt/atomun-docker-build

## Tag Signing

Tags will be signed by the following privately held hardware-based GPG key.

    pub   3072R/B1DBAD54 2011-04-19
          Key fingerprint = 2F0A FF2E A8A0 1485 C95B  8650 F0A4 C0F7 B1DB AD54
    uid                  Thomas Harning Jr <harningt@gmail.com>


[MIT]: https://opensource.org/licenses/MIT
[SemVer2.0]: http://semver.org/spec/v2.0.0.html
