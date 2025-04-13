# doom-emacs-macos
## clone 
```shell
git clone --branch emacs-30.1 --depth 1 git://git.sv.gnu.org/emacs.git
```
```shell
./autogen.sh
```
```shell
./configure --with-native-compilation \
            --with-modules \
            --with-json \
            --with-gnutls \
            --with-xml2
```
```shell
make -j$(sysctl -n hw.ncpu)
```
```shell
make install
```
