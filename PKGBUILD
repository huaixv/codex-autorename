# Maintainer: pc
pkgname=codex-autorename
pkgver=0.1.0
pkgrel=2
pkgdesc='Rename Codex threads from the initial prompt'
arch=('any')
url='https://github.com/openai/codex'
license=('unknown')
depends=('nodejs')
optdepends=('openai-codex: real Codex CLI resolved from PATH')
source=("codex-autorename"
        "codex-batch-rename")
sha256sums=('aa740ccef26e8b5606e3222c76f48430c6fca67d0a6697ec883eefdc6016cabf'
            '1d6810acd712f890386240bf654b7f2984924968fd45dfc8698dfab2de52bbfc')

package() {
  install -Dm755 "${srcdir}/codex-autorename" "${pkgdir}/usr/bin/codex-autorename"
  install -Dm755 "${srcdir}/codex-batch-rename" "${pkgdir}/usr/bin/codex-batch-rename"
}
