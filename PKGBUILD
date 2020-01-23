pkgname=teradata-jdbc
pkgver=16.20.00.13
pkgrel=1
pkgdesc="Teradata JDBC Driver"
arch=('any')
url="http://downloads.teradata.com/download/connectivity/jdbc-driver"
license=('Proprietary')
depends=('java-runtime-openjdk')

source=("TeraJDBC__indep_indep.${pkgver}.tar")
md5sums=('4787c77d30f0cc93bddcf5da79e64248')

package() {
  install -dm755 ${pkgdir}/opt/teradata/jdbc
  tar -xvaf ${srcdir}/TeraJDBC__indep_indep.${pkgver}.tar -C ${pkgdir}/opt/teradata/jdbc/
}
