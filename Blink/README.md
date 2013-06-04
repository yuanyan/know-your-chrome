## 源码目录结构


```sh
 Source
    ├─bindings
    │  ├─scripts
    │  ├─tests
    │  │  ├─idls
    │  │  └─results
    │  └─v8
    │     └─custom
    ├─core
    │  ├─accessibility
    │  ├─animation
    │  ├─core.gyp
    │  │  ├─mac
    │  │  └─scripts
    │  ├─css
    │  ├─dom
    │  │  └─default
    │  │      └─chromium
    │  ├─editing
    │  │  └─chromium
    │  ├─fileapi
    │  ├─history
    │  ├─html
    │  │  ├─canvas
    │  │  ├─parser
    │  │  ├─shadow
    │  │  └─track
    │  ├─icu
    │  │  └─unicode
    │  ├─inspector
    │  ├─loader
    │  │  ├─appcache
    │  │  ├─archive
    │  │  └─cache
    │  ├─mathml
    │  ├─page
    │  │  ├─animation
    │  │  └─scrolling
    │  ├─platform
    │  │  ├─animation
    │  │  ├─audio
    │  │  │  ├─chromium
    │  │  │  ├─ffmpeg
    │  │  │  ├─ipp
    │  │  │  ├─mac
    │  │  │  ├─mkl
    │  │  │  └─resources
    │  │  ├─chromium
    │  │  │  └─support
    │  │  ├─cocoa
    │  │  ├─graphics
    │  │  │  ├─cg
    │  │  │  ├─chromium
    │  │  │  ├─cocoa
    │  │  │  ├─cpu
    │  │  │  │  └─arm
    │  │  │  │      └─filters
    │  │  │  ├─filters
    │  │  │  │  └─custom
    │  │  │  ├─gpu
    │  │  │  ├─harfbuzz
    │  │  │  ├─mac
    │  │  │  ├─opentype
    │  │  │  ├─skia
    │  │  │  └─transforms
    │  │  ├─image-decoders
    │  │  │  ├─bmp
    │  │  │  ├─gif
    │  │  │  ├─ico
    │  │  │  ├─jpeg
    │  │  │  ├─png
    │  │  │  ├─skia
    │  │  │  └─webp
    │  │  ├─image-encoders
    │  │  │  └─skia
    │  │  ├─leveldb
    │  │  ├─mac
    │  │  ├─mediastream
    │  │  │  └─chromium
    │  │  ├─mock
    │  │  ├─network
    │  │  ├─sql
    │  │  │  └─chromium
    │  │  ├─text
    │  │  │  ├─cf
    │  │  │  ├─chromium
    │  │  │  ├─mac
    │  │  │  ├─transcoder
    │  │  │  └─win
    │  │  └─win
    │  ├─plugins
    │  ├─rendering
    │  │  ├─exclusions
    │  │  ├─style
    │  │  └─svg
    │  ├─Resources
    │  │  └─pagepopups
    │  │      └─chromium
    │  ├─scripts
    │  ├─storage
    │  ├─svg
    │  │  ├─animation
    │  │  ├─graphics
    │  │  │  └─filters
    │  │  └─properties
    │  ├─testing
    │  │  └─v8
    │  ├─tests
    │  ├─workers
    │  └─xml
    │      └─parser
    ├─devtools
    │  ├─front_end
    │  │  ├─cm
    │  │  ├─Images
    │  │  │  └─src
    │  │  └─UglifyJS
    │  └─scripts
    │      └─closure
    ├─modules
    │  ├─battery
    │  ├─device_orientation
    │  ├─donottrack
    │  ├─encryptedmedia
    │  ├─filesystem
    │  ├─gamepad
    │  ├─geolocation
    │  ├─indexeddb
    │  │  └─chromium
    │  ├─inputmethod
    │  ├─mediasource
    │  ├─mediastream
    │  ├─navigatorcontentutils
    │  ├─notifications
    │  ├─quota
    │  ├─speech
    │  │  └─chromium
    │  ├─vibration
    │  ├─webaudio
    │  ├─webdatabase
    │  │  └─chromium
    │  ├─webmidi
    │  └─websockets
    ├─Platform
    │  ├─chromium
    │  │  └─public
    │  │      ├─android
    │  │      ├─default
    │  │      ├─linux
    │  │      ├─mac
    │  │      └─win
    │  └─Platform.gyp
    ├─WebKit
    │  └─chromium
    │      ├─public
    │      │  ├─android
    │      │  ├─default
    │      │  ├─gtk
    │      │  ├─linux
    │      │  ├─mac
    │      │  ├─win
    │      │  └─x11
    │      ├─src
    │      │  ├─android
    │      │  ├─default
    │      │  ├─gtk
    │      │  ├─linux
    │      │  ├─mac
    │      │  ├─painting
    │      │  ├─win
    │      │  └─x11
    │      └─tests
    │          └─data
    │              ├─listener
    │              ├─pageserialization
    │              ├─pageserializer
    │              ├─popup
    │              └─prerender
    └─wtf
        ├─chromium
        ├─dtoa
        ├─os-win32
        ├─tests
        ├─text
        └─unicode
            └─icu
```            
            
