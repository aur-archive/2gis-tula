# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-tula
pkgver=24
pkgrel=1
pkgdesc="Map of Tula for 2GIS, November 2012"
arch=('i686' 'x86_64')
url="http://tula.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.9.0.1')
source=("http://download.2gis.ru/arhives/2GISData_Tula-24.orig.zip")
md5sums=('a22e02166e62fbf3e11d909550cad97e')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Tula.dgdat "${startdir}/pkg/opt/2gis/tula.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Tula.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Tula.dglf" || return 1
     
}

