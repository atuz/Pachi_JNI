# Pachi_JNI

This is the Android version of [Pachi][1], a Go game engine developed by Petr Baudis and Jean-Loup Gailly.

If you make a change to Pachi's code, you have to rebuild the executable with the [Android NDK][2].  
To do this, open the `jni` folder and enter the command `ndk-build`. If you get errors, try to use the NDK version r10e. Sometimes newer versions require to make some changes to the code. Then copy the executable from `libs/armeabi` to the `app/src/main/res/raw` folder and replace the existing one.


## Credits

- [The Pachi project](http://pachi.or.cz)
- [go game](https://github.com/atuz/Game-for-Go)


## License

Pachi is distributed under the GPLv2 license (see the COPYING file for details and full text of the license). You are welcome to tweak it as you wish and distribute it freely, but only together with the source code.

  [1]: http://pachi.or.cz
  [2]: http://developer.android.com/tools/sdk/ndk/index.html
