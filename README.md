# Debian security backports

Independent security backports for Debian releases. Each entry contains a reviewable patch, its upstream provenance, and build or verification instructions. These are not official Debian or Freexian updates.

| Release | Package | Backport |
| --- | --- | --- |
| Debian 11 (Bullseye) | zlib | [CVE-2026-85091](bullseye/zlib/CVE-2026-85091/README.md) |

The zlib patch can be used with standard Debian packaging tools. The Reploy container recipe is optional. Review the patch and any tooling you choose to use before running it.

Original material in this repository is available under the [MIT License](LICENSE). Third-party material retains its own licenses and notices, including the [zlib license](bullseye/zlib/CVE-2026-85091/LICENSE.zlib) for the adapted patch.
