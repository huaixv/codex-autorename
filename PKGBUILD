# Maintainer: pc
pkgname=codex-autorename
pkgver=0.1.0
pkgrel=1
pkgdesc='Codex wrapper that auto-renames threads from the initial prompt'
arch=('any')
url='https://github.com/openai/codex'
license=('unknown')
depends=('nodejs')
optdepends=('codex: default real Codex CLI invoked at /usr/bin/codex')
source=("${pkgname}")
sha256sums=('00279cd735a627b877749c09d293be7f737efb0a980495855f6095b1738da804')

package() {
  install -Dm755 "${srcdir}/${pkgname}" "${pkgdir}/usr/bin/${pkgname}"
}
