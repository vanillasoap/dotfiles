#!/usr/bin/env bash

# Install command-line tools
xcode select --install

# Install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# Make sure we’re using the latest Homebrew.
brew update

# Upgrade any already-installed formulae.
brew upgrade

# Save Homebrew’s installed location.
BREW_PREFIX=$(brew --prefix)

# Install GNU core utilities (those that come with macOS are outdated).
echo Don’t forget to add '$(brew --prefix coreutils)/libexec/gnubin' to '$PATH'
brew install coreutils
ln -s "${BREW_PREFIX}/bin/gsha256sum" "${BREW_PREFIX}/bin/sha256sum"

# Install some other useful utilities like `sponge`.
brew install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed.
brew install findutils
# Install GNU `sed`
brew install gnu-sed
# Install Zsh
brew install zsh
# Switch to using brew-installed bash as default shell
if ! fgrep -q "${BREW_PREFIX}/bin/zsh" /etc/shells; then
    echo "${BREW_PREFIX}/bin/zsh" | sudo tee -a /etc/shells
    chsh -s "${BREW_PREFIX}/bin/zsh"
fi

brew install adns
brew install ansiweather
brew install ant
brew install aom
brew install apr
brew install apr-util
brew install aptly
brew install argon2
brew install aria2
brew install armadillo
brew install arpack
brew install asciidoctor
brew install asio
brew install aspell
brew install astyle
brew install atk
brew install autoconf
brew install automake
brew install avr-binutils
brew install avr-gcc
brew install avrdude
brew install bash
brew install bash-completion
brew install bat
brew install bdw-gc
brew install bison
brew install bitlbee
brew install blueutil
brew install boost
brew install botan
brew install brotli
brew install byacc
brew install bzip2
brew install c-ares
brew install cairo
brew install cartr/qt4/qt-webkit@2.3
brew install castxml
brew install ccache
brew install ceres-solver
brew install cfitsio
brew install cgal
brew install cjbassi/gotop/gotop
brew install cmake
brew install cmatrix
brew install cminpack
brew install coreutils
brew install cppunit
brew install curl
brew install curl-openssl
brew install cython
brew install dav1d
brew install dbus
brew install dcmtk
brew install dcraw
brew install desktop-file-utils
brew install dfu-programmer
brew install diffutils
brew install djvulibre
brew install docbook
brew install docbook-xsl
brew install double-conversion
brew install doxygen
brew install eddieantonio/eddieantonio/imgcat
brew install eigen
brew install emacs
brew install epsilon
brew install eslint
brew install exa
brew install exact-image
brew install exiftool
brew install exiv2
brew install expat
brew install faac
brew install faad2
brew install fcgi
brew install fd
brew install fdk-aac
brew install feh
brew install fff
brew install ffmpeg
brew install ffmpeg2theora
brew install fftw
brew install findutils
brew install flac
brew install flake8
brew install flann
brew install flex
brew install fluid-synth
brew install fontconfig
brew install freeglut
brew install freeimage
brew install freetds
brew install freetype
brew install freexl
brew install frei0r
brew install fribidi
brew install fzf
brew install gawk
brew install gcc
brew install gd
brew install gdb
brew install gdbm
brew install gdk-pixbuf
brew install geoip
brew install geos
brew install gettext
brew install gflags
brew install ghostscript
brew install giflib
brew install git
brew install git-lfs
brew install gl2ps
brew install glew
brew install glfw
brew install glib
brew install glib-networking
brew install glog
brew install gmp
brew install gnu-getopt
brew install gnu-sed
brew install gnu-tar
brew install gnupg
brew install gnuplot
brew install gnutls
brew install go
brew install gobject-introspection
brew install gotop
brew install gperf
brew install gphoto2
brew install gpsbabel
brew install gptfdisk
brew install gradle
brew install graphene
brew install graphite2
brew install graphviz
brew install grep
brew install gsettings-desktop-schemas
brew install gsl
brew install gst-plugins-bad
brew install gst-plugins-base
brew install gst-plugins-good
brew install gst-plugins-ugly
brew install gst-python
brew install gstreamer
brew install gtk+
brew install gtk+3
brew install gtkglext
brew install gts
brew install guile
brew install gulp-cli
brew install harfbuzz
brew install hdf5
brew install help2man
brew install hexyl
brew install hicolor-icon-theme
brew install highlight
brew install htop
brew install hwloc
brew install icu4c
brew install ifstat
brew install ilmbase
brew install imagemagick
brew install imgcat
brew install imlib2
brew install inetutils
brew install isl
brew install ivandokov/contrib/phockup
brew install jansson
brew install jasper
brew install jemalloc
brew install jpeg
brew install jpeg-turbo
brew install jq
brew install json-c
brew install json-glib
brew install jsoncpp
brew install khanhas/tap/spicetify-cli
brew install krb5
brew install lame
brew install lapack
brew install laszip
brew install lbzip2
brew install leptonica
brew install libagg
brew install libao
brew install libarchive
brew install libass
brew install libassuan
brew install libav
brew install libb2
brew install libbluray
brew install libcerf
brew install libcroco
brew install libcuefile
brew install libdap
brew install libde265
brew install libelf
brew install libepoxy
brew install libev
brew install libevent
brew install libexif
brew install libffi
brew install libftdi0
brew install libgcrypt
brew install libglade
brew install libgpg-error
brew install libgphoto2
brew install libharu
brew install libheif
brew install libhid
brew install libiconv
brew install libid3tag
brew install libidn
brew install libidn2
brew install libkate
brew install libksba
brew install liblqr
brew install libmaxminddb
brew install libmetalink
brew install libmms
brew install libmpc
brew install libmpdclient
brew install libnfs
brew install libnice
brew install libogg
brew install libomp
brew install libpcap
brew install libpng
brew install libpq
brew install libpsl
brew install libreplaygain
brew install librsvg
brew install libsamplerate
brew install libsass
brew install libscrypt
brew install libshout
brew install libsndfile
brew install libsodium
brew install libsoup
brew install libsoxr
brew install libspotify
brew install libssh
brew install libssh2
brew install libsvg
brew install libsvg-cairo
brew install libsvm
brew install libtasn1
brew install libtermkey
brew install libtiff
brew install libtool
brew install libunistring
brew install libupnp
brew install libusb
brew install libusb-compat
brew install libusrsctp
brew install libuv
brew install libvidstab
brew install libvorbis
brew install libvpx
brew install libvterm
brew install libxml2
brew install libxslt
brew install libyaml
brew install libzip
brew install lighttpd
brew install little-cms2
brew install llvm
brew install lolcat
brew install lua
brew install lua@5.1
brew install luajit
brew install lunchy
brew install lynx
brew install lz4
brew install lzo
brew install m-cli
brew install mad
brew install mas
brew install mdbtools
brew install mesa
brew install meson
brew install metis
brew install minizip
brew install mono
brew install moreutils
brew install mpc
brew install mpd
brew install mpfr
brew install mpv
brew install msgpack
brew install mujs
brew install muparser
brew install mupdf-tools
brew install musepack
brew install mysql
brew install mysql-client
brew install mysql@5.7
brew install nasm
brew install ncmpcpp
brew install ncurses
brew install neofetch
brew install neovim
brew install netcat
brew install netcdf
brew install netpbm
brew install nettle
brew install nghttp2
brew install ninja
brew install nmap
brew install node
brew install npth
brew install nspr
brew install nss
brew install ntopng
brew install numpy
brew install oniguruma
brew install open-mpi
brew install openblas
brew install opencore-amr
brew install opencv
brew install openexr
brew install openjdk
brew install openjpeg
brew install openldap
brew install openslide
brew install openssl@1.0
brew install openssl@1.1
brew install openvpn
brew install opus
brew install opusfile
brew install orc
brew install osx-cross/avr/avr-gcc
brew install p11-kit
brew install p7zip
brew install pango
brew install pcre
brew install pcre2
brew install pegtl
brew install perl
brew install phockup
brew install php
brew install pidof
brew install pinentry
brew install pipes-sh
brew install pixman
brew install pkcs11-helper
brew install pkg-config
brew install podofo
brew install poppler
brew install popt
brew install portaudio
brew install potrace
brew install powerlevel10k
brew install pr0d1r2/python2/python@2.7.17
brew install prettier
brew install protobuf
brew install protobuf-c
brew install pth
brew install pugixml
brew install pv
brew install py2cairo
brew install py3cairo
brew install pybind11
brew install pygobject3
brew install pylint
brew install pyqt
brew install pyside
brew install pyspotify
brew install python@2.7.17
brew install python@3.8
brew install qca
brew install qhull
brew install qjson
brew install qt
brew install qt-webkit@2.3
brew install qt@4
brew install quilt
brew install qwt
brew install qwtpolar
brew install r
brew install rav1e
brew install readline
brew install redis
brew install redshift
brew install regex-opt
brew install rmtrash
brew install romkatv/powerlevel10k/powerlevel10k
brew install rrdtool
brew install rsync
brew install rtmpdump
brew install rubberband
brew install ruby
brew install sassc
brew install scipy
brew install screenresolution
brew install sdl
brew install sdl2
brew install sfcgal
brew install shapelib
brew install shared-mime-info
brew install shfmt
brew install sip
brew install skhd
brew install sleepwatcher
brew install snappy
brew install sox
brew install spatialindex
brew install spawn-fcgi
brew install speex
brew install sphinx
brew install spicetify-cli
brew install sqlite
brew install srt
brew install srtp
brew install subversion
brew install suite-sparse
brew install superlu
brew install svg2pdf
brew install swig
brew install szip
brew install taglib
brew install tbb
brew install tcl-tk
brew install terminal-notifier
brew install tesseract
brew install tesseract-lang
brew install texinfo
brew install theora
brew install tidy-html5
brew install tinyxml
brew install tmux
brew install tor
brew install torsocks
brew install tree
brew install twine-pypi
brew install uchardet
brew install ufraw
brew install unbound
brew install unibilium
brew install unixodbc
brew install utf8proc
brew install utimer
brew install v8
brew install vala
brew install vapoursynth
brew install vim
brew install vtk
brew install watchman
brew install watson
brew install webp
brew install weechat
brew install wget
brew install wxmac
brew install wxpython
brew install x264
brew install x265
brew install xerces-c
brew install xmlto
brew install xvid
brew install xxhash
brew install xz
brew install yabai
brew install yasm
brew install you-get
brew install youtube-dl
brew install zimg
brew install zlib
brew install zstd

# install node + npm packages
#curl -sL install-node.now.sh/lts | bash
brew install yarn
npm install -g bullshit-generator
npm install -g capture-website-cli
npm install -g cjsx-codemod
npm install -g clean-css-cli
npm install -g csscleanerpro
npm install -g csslint
npm install -g gtop
npm install -g icon-gen
npm install -g idea
npm install -g install-peerdeps
npm install -g js2coffee
npm install -g less
npm install -g milligram-cli
npm install -g node-cipher
npm install -g npm
npm install -g npm-install-peers
npm install -g organize-cli
npm install -g pageres
npm install -g pageres-cli
npm install -g pdf2image
npm install -g pdf2images
npm install -g peerflix
npm install -g postcss-cli
npm install -g postcss-sorting
npm install -g purify-css
npm install -g sass
npm install -g stylelint
npm install -g vsce

# Yabai
brew tap koekeishiya/formulae
brew install koekeishiya/formulae/skhd
brew install koekeishiya/formulae/yabai

# mopidy
brew tap mopidy/mopidy
brew install mopidy
brew install mopidy-local
brew install mopidy-mpd
brew install mopidy-spotify
brew install mopidy/mopidy/mopidy-local
brew install mopidy/mopidy/mopidy-mpd
brew install mopidy/mopidy/mopidy-spotify

# cask
brew tap caskroom/cask
brew cask install adoptopenjdk8
brew cask install elektriktrick
brew cask install font-iosevka
brew cask install gitbook
brew cask install google-chrome
brew cask install java
brew cask install logitech-options
brew cask install lunchy
brew cask install mono-mdk
brew cask install osxfuse
brew cask install phantomjs
brew cask install qlcolorcode
brew cask install qlimagesize
brew cask install qlmarkdown
brew cask install qlstephen
brew cask install qlvideo
brew cask install qmk-toolbox
brew cask install qt-creator
brew cask install quicklook-json
brew cask install quicklookase
brew cask install rar
brew cask install sublime-text
brew cask install ubersicht
brew cask install xquartz
brew cask install the-unarchiver
brew cask install iterm2

# A little update, just in case
brew update
brew upgrade

# Remove old versions from cellar
brew cleanup
brew cleanup -s
