# Maintainer: mirsella <mirsella@protonmail.com>
pkgname=tokenuze-bin
pkgver=0.9.0
pkgrel=2
pkgdesc="A CLI tool that summarizes token and cost usage from various LLM providers"
arch=('x86_64')
url="https://github.com/arrufat/tokenuze"
license=('MIT')
optdepends=('sqlite: for Zed and Crush providers')
provides=('tokenuze')
conflicts=('tokenuze')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/arrufat/tokenuze/releases/download/${pkgver}/tokenuze-linux-x86_64.tar.gz")
sha256sums=('804266a590f7b8cba00cbbdd9f336fdab35acb8b45ed4ae11084d184359463ee')

package() {
    install -Dm755 tokenuze "${pkgdir}/usr/bin/tokenuze"
}
