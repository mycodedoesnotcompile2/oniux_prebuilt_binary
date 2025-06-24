TOR oniux prebuilt binaries
===========================

Description
-----------
The great ["oniux"](https://blog.torproject.org/introducing-oniux-tor-isolation-using-linux-namespaces/) tool, from the TOR project, automatically compiled when there is a new release.

The building workflow is [here](https://github.com/mycodedoesnotcompile2/oniux_prebuilt_binary/blob/main/.github/workflows/main.yml).

See the [Github release page](https://github.com/mycodedoesnotcompile2/oniux_prebuilt_binary/releases) of this repository to access prebuilt binaries for different architectures (x64, arm5/7/64) and different libc (GNU, musl).

For each release here, the tag corresponds to the latest short commit ID `git rev-parse --short HEAD` of the current latest main branch of [oniux Gitlab repository](https://gitlab.torproject.org/tpo/core/oniux).

Copyright and license
---------------------
- All trademarks, service marks, trade names and product names appearing on this repository are the property of their respective owners
- Anything published here follows, and uses, the same licences than the upstream oniux project
- I don't work or be affiliated with the TOR project
