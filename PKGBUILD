# Maintainer: pc
pkgname=codex-autorename
pkgver=0.1.0
pkgrel=1
pkgdesc='Rename Codex threads from the initial prompt'
arch=('any')
url='https://github.com/openai/codex'
license=('unknown')
depends=('nodejs')
optdepends=('openai-codex: real Codex CLI resolved from PATH')
source=("codex-autorename"
        "codex-batch-rename")
sha256sums=('55d60e4985ff2d2f4d9ba48fb4a5722089f90f3394dea93c089a99fb1840f8b5'
            '1d6810acd712f890386240bf654b7f2984924968fd45dfc8698dfab2de52bbfc')

package() {
  install -Dm755 "${srcdir}/codex-autorename" "${pkgdir}/usr/bin/codex-autorename"
  install -Dm755 "${srcdir}/codex-batch-rename" "${pkgdir}/usr/bin/codex-batch-rename"
}
