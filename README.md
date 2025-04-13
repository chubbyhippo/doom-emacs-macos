# doom-emacs-macos
## clone 
```shell
git clone --branch emacs-30.1 --depth 1 git://git.sv.gnu.org/emacs.git
```
```shell
./autogen.sh
```
```shell
./configure --with-native-compilation
```
```shell
make -jN (N = number of cores you have in your cpu)
```
```shell
make install
```
