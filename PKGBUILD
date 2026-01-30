# Maintainer: mirsella <mirsella@protonmail.com>
pkgname=tokenuze-bin
pkgver=0.8.0
pkgrel=1
pkgdesc="A CLI tool that summarizes token and cost usage from various LLM providers"
arch=('x86_64')
url="https://github.com/bfactory-ai/tokenuze"
license=('MIT')
optdepends=('sqlite: for Zed and Crush providers')
provides=('tokenuze')
conflicts=('tokenuze')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/bfactory-ai/tokenuze/releases/download/${pkgver}/tokenuze-linux-x86_64.tar.gz")
sha256sums=('e1a915265b43badc222dec2784bf8e28624ea10d600245275b18f43ce8dcfe13')

package() {
    install -Dm755 tokenuze "${pkgdir}/usr/bin/tokenuze"
}
