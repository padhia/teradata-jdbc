pkgname=teradata-jdbc
pkgver=16.20.00.12
pkgrel=1
pkgdesc="Teradata JDBC Driver"
arch=('any')
url="http://downloads.teradata.com/download/connectivity/jdbc-driver"
license=('Proprietary')
depends=('java-runtime-openjdk')

source=("TeraJDBC__indep_indep.${pkgver}.tar")
md5sums=('e8ed5e8e4dfb31d4ea1bab38401d61b2')

package() {
  install -dm755 ${pkgdir}/opt/teradata/jdbc
  tar -xvaf ${srcdir}/TeraJDBC__indep_indep.${pkgver}.tar -C ${pkgdir}/opt/teradata/jdbc/
}
