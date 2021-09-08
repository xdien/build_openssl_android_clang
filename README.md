# build_openssl_android_clang
- Openssl 1.1.1 auto build script for android, short, simple, with android ndk clang 
- You will find many ways to build openssl for android on the internet. That causes many difficulties for newcomers. I created this script to simplify the download and build process of openssl for android with android ndk(23) clang 
# Requerenment
- OS: linux
- Android ndk 21 or later. you can download the ndk here https://developer.android.com/ndk/downloads
# Run script
```
$ git clone https://github.com/xdien/build_openssl_android_clang
$ cd build_openssl_android_clang
$ chmod +x build_openssl.sh
$ ./build_openssl.sh
```
- You will find the library at ./libs/android/clang directory after successfully running the script 
# Screenshots
 ![Openssl library folder built successfully](/screenshots/sc_1.png)
 
 ![openssl dynamic library](/screenshots/sc_2.png)
