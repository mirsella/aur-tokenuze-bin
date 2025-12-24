# Maintainer: mirsella <mirsella@protonmail.com>
pkgname=tokenuze-bin
pkgver=0.7.1
pkgrel=1
pkgdesc="A CLI tool that summarizes token and cost usage from various LLM providers"
arch=('x86_64')
url="https://github.com/bfactory-ai/tokenuze"
license=('MIT')
optdepends=('sqlite: for Zed and Crush providers')
provides=('tokenuze')
conflicts=('tokenuze')
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/bfactory-ai/tokenuze/releases/download/${pkgver}/tokenuze-linux-x86_64.tar.gz")
sha256sums=('a04df24541472c5807356fd33530a9c8c3392ab7b012b7cb71784a2f7c4c0e2d')

package() {
    install -Dm755 tokenuze "${pkgdir}/usr/bin/tokenuze"
}
