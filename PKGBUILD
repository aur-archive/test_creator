# Maintainer: pycat <maciej.kociuba@gmail.com>
# Previous maintainer: Maciej Kociuba <maciej.kociuba@gmail.com>

pkgname=test_creator
pkgver=0.1.2
pkgrel=2
pkgdesc='Simple program for teachers which want to create, storage and generate random tests'
arch=('any')
url='https://github.com/pycat/test_creator/'
license=('GPL')
depends=('python>=3' 'pyqt>=4' 'qt4>=4')
conflicts=('test_creator-git')
source=("http://github.com/pycat/test_creator/raw/master/${pkgname}-${pkgver}.tar.gz")

build() { 
  cd "${srcdir}/${pkgname}-${pkgver}"

  # Replace "python" with the python binary you want ranger to use!
  # (python 2.6 and >=3.1 supported, below 2.6 will certainly not work.)
  python setup.py -q install --root="${pkgdir}" --optimize=1
}

md5sums=('0a2aa84c327afc2b2d07ead20fba9b36')
