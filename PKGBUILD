#Contributor: Lewis "mystax" Hulbert <mystax@wagn.me>
#Maintainer: Lewis "mystax" Hulbert <mystax@wagn.me>
pkgname=craftbukkit-plugin-horseutils
pkgver=0.2
pkgrel=1
pkgdesc="Craftbukkit mod that allows you to god, lock, direct claim and nickname horses."
arch=(any)
url="http://dev.bukkit.org/bukkit-plugins/horseutils/"
license=("LGPLv3")
depends=("craftbukkit")
source=("http://dev.bukkit.org/media/files/721/710/HorseUtils-V0.2.jar")
noextract=("HorseUtils-V0.2.jar")
md5sums=('3524f1c23b40375a9d5f036cfb5cd775')

package() {
  install -Dm644 "$srcdir/HorseUtils-V0.2.jar" "$pkgdir/srv/craftbukkit/plugins/HorseUtils-V0.2.jar"
}

# vim:set ts=2 sw=2 et:
