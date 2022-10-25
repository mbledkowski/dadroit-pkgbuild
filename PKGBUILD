# Maintainer: mble <pub@mble.dk>
pkgname=dadroit-viewer
_name=DaDroit\ Viewer
pkgver=2.0\ Build\ 537
pkgrel=1
pkgdesc="Open BIG JSON data in a blink."
arch=('x86_64')
url="https://dadroit.com/"
license=('custom:dadroit')
# todo: deps and settings
depends=()
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()

source=("https://dadroit.com/releases/lnx/${_name}%20${pkgver}%20x64.AppImage")
sha256sums=('541a7bba06c96283a1777302f9437c4ea2d1706b904ef37df3260dcb1a4eb12c')


package() {
  local _dest="${pkgdir}/opt/${pkgname}"
  local _share="${pkgdir}/usr/share"
        
  exec ${srcdir}/${_name}%20${pkgver}%20x64.AppImage --appimage-extract
  
}
