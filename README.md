# doom-emacs-macos
```shell
git clone --branch emacs-30.1 --depth 1 git://git.sv.gnu.org/emacs.git
```
```shell
./autogen.sh
```
```shell
./configure --with-native-compilation \
            --with-xwidgets
```
```shell
make -j$(sysctl -n hw.ncpu)
```
```shell
make install
```
```shell
rm -rf ~/Application/Emacs.app && mv nextstep/Emacs.app ~/Applications/Emacs.app
```
```shell
git clone --depth 1 https://github.com/doomemacs/doomemacs ~/.config/emacs
~/.config/emacs/bin/doom install
```
```shell
doom doctor
```
