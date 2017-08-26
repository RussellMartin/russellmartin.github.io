cmake_minimum_required(VERSION 3.8)
project(russellmartin_github_io)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        assets/css/images/bg.jpg
        assets/css/images/overlay.png
        assets/css/font-awesome.min.css
        assets/css/ie8.css
        assets/css/main.css
        assets/css/noscript.css
        assets/fonts/fontawesome-webfont.eot
        assets/fonts/fontawesome-webfont.svg
        assets/fonts/fontawesome-webfont.ttf
        assets/fonts/fontawesome-webfont.woff
        assets/fonts/fontawesome-webfont.woff2
        assets/fonts/FontAwesome.otf
        assets/js/ie/backgroundsize.min.htc
        assets/js/ie/html5shiv.js
        assets/js/ie/respond.min.js
        assets/js/jquery.min.js
        assets/js/main.js
        assets/js/skel-viewport.min.js
        assets/js/skel.min.js
        assets/js/util.js
        assets/sass/libs/_functions.scss
        assets/sass/libs/_mixins.scss
        assets/sass/libs/_skel.scss
        assets/sass/libs/_vars.scss
        assets/sass/ie8.scss
        assets/sass/main.scss
        assets/sass/noscript.scss
        images/me.jpg
        images/pic01.jpg
        images/pic02.jpg
        images/pic03.jpg
        images/pic04.jpg
        images/pic05.jpg
        images/pic06.jpg
        images/pic07.jpg
        images/pic08.jpg
        images/pic09.jpg
        images/pic10.jpg
        images/pic11.jpg
        images/pic12.jpg
        index.html
        LICENSE.txt
        README.txt)

add_executable(russellmartin_github_io ${SOURCE_FILES})