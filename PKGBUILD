# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>

pkgname=2gis-tula
pkgver=6
pkgrel=1
pkgdesc="Map of Tula for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Tula-${pkgver}.orig.zip")
md5sums=('16db247d38da1d5f461661a4a9971601')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Tula.dgdat "${startdir}/pkg/opt/2gis/tula.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Tula.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Tula.dglf" || return 1

}

