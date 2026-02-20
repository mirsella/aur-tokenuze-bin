# Maintainer: mirsella <mirsella@protonmail.com>
pkgname=tokenuze-bin
pkgver=0.9.1
pkgrel=1
pkgdesc="A CLI tool that summarizes token and cost usage from various LLM providers (fork with opencode.db support)"
arch=('x86_64')
url="https://github.com/mirsella/tokenuze"
license=('MIT')
optdepends=('sqlite: for Zed, Crush, and Opencode SQLite providers')
provides=('tokenuze')
conflicts=('tokenuze')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/mirsella/tokenuze/releases/download/${pkgver}/tokenuze-linux-x86_64.tar.gz")
sha256sums=('d7c27930dfc7ef3ed473cf0137beee27d0b7dc516d1032b1f51c1699889283c7')

package() {
    install -Dm755 tokenuze "${pkgdir}/usr/bin/tokenuze"
}
