# fsearch-archlinux-bin

Prebuilt FSearch binaries for the Arch Linux family (`x86_64`, `x86_64_v3`,
`aarch64`, `riscv64`, `armv7h`), built from [`fr0stb1rd/fsearch`](https://github.com/fr0stb1rd/fsearch) tags.

## How it works

Actions → `release-bin` → Run workflow → enter a source tag (e.g. `0.3.1-2`).
Each architecture is built in its official Arch-lineage environment
(`archlinux:latest` container, ALARM / Arch RISC-V rootfs) and the tarballs
are attached to a release of the same name in this repo.

## AUR

The `fsearch-bin` AUR package consumes these release tarballs
(`packaging/aur-bin/PKGBUILD`, coming soon).

## License

[MIT](LICENSE) — FSearch itself is [GPL-2.0-or-later](https://github.com/fr0stb1rd/fsearch/blob/master/LICENSE).
