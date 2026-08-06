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
sha256sums=('b3f5f584aa657669992764a64cb00b9c2c022f22c7dc57eb1e53356112b23b2f'
            'a3513b65954f2db41f58cd3ced0e8062e376394ff76d7e14d87e0563b77c4a1e')

package() {
  install -Dm755 "${srcdir}/codex-autorename" "${pkgdir}/usr/bin/codex-autorename"
  install -Dm755 "${srcdir}/codex-batch-rename" "${pkgdir}/usr/bin/codex-batch-rename"
}
