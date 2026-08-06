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
sha256sums=('0d0064409c3a75e68e675d196818411ee53d128a16ec379f259f2c63ff169739'
            'e0a72cfaacad08652b21654b0f286cb8c3aac97a61894cb5e164376b30df60e4')

package() {
  install -Dm755 "${srcdir}/codex-autorename" "${pkgdir}/usr/bin/codex-autorename"
  install -Dm755 "${srcdir}/codex-batch-rename" "${pkgdir}/usr/bin/codex-batch-rename"
}
