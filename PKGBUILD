# Maintainer: pc
pkgname=codex-autorename
pkgver=0.1.0
pkgrel=1
pkgdesc='Rename Codex threads from the initial prompt'
arch=('any')
url='https://github.com/openai/codex'
license=('unknown')
depends=('nodejs')
optdepends=('openai-codex: default real Codex CLI invoked at /usr/bin/codex')
source=("codex-autorename"
        "codex-batch-rename")
sha256sums=('00279cd735a627b877749c09d293be7f737efb0a980495855f6095b1738da804'
            'f20ba17ca7b84a04b9d9f2765828cc84b7a95f6a49aff16952c3a8a675186186')

package() {
  install -Dm755 "${srcdir}/codex-autorename" "${pkgdir}/usr/bin/codex-autorename"
  install -Dm755 "${srcdir}/codex-batch-rename" "${pkgdir}/usr/bin/codex-batch-rename"
}
