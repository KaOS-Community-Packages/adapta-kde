pkgname=adapta-kde
pkgver=20180828
pkgrel=1
pkgdesc="An adaptive QT theme based on Adapta GTK using Material Design Guidelines"
arch=('x86_64')
url="https://github.com/PapirusDevelopmentTeam/${pkgname}"
license=('GPL3')
depends=('kvantum')
options=('!strip')
source=("${url}/archive/${pkgver}.tar.gz")
md5sums=('0f7382fd707e8b95567164237621f027')

package() {
    cd ${pkgbase}-${pkgver}
    install -d "${pkgdir}"/usr/share
 
    cp -r Kvantum "${pkgdir}"/usr/share
    cp -r aurorae "${pkgdir}"/usr/share
    cp -r color-schemes "${pkgdir}"/usr/share
    cp -r konsole "${pkgdir}"/usr/share
    cp -r plasma "${pkgdir}"/usr/share
    cp -r wallpapers "${pkgdir}"/usr/share
    cp -r yakuake "${pkgdir}"/usr/share
}
