
![](https://raw.githubusercontent.com/slightech/MYNT-EYE-SDK/master/mynteye.png)

# MYNT EYE SDK

## Guides

* [Documentation](https://slightech.github.io/MYNT-EYE-SDK)

## Samples

Samples about how to use MYNT EYE camera in some popular projects.

* [MYNT-EYE-OKVIS-Sample](https://github.com/slightech/MYNT-EYE-OKVIS-Sample)
* [MYNT-EYE-ORB-SLAM2-Sample](https://github.com/slightech/MYNT-EYE-ORB-SLAM2-Sample)

## Integrations

Integrations let you use the MYNT EYE camera in some different environments.

* [MYNT-EYE-ROS-Wrapper](https://github.com/slightech/MYNT-EYE-ROS-Wrapper)

## Getting Started

Download and unzip the SDK in "Archives" section according to your OS. Then follow the "README" in SDK directory or these online docs to setup it:

* [Getting Started on Linux](https://slightech.github.io/MYNT-EYE-SDK/getting_started_linux.html)
* [Getting Started on macOS](https://slightech.github.io/MYNT-EYE-SDK/getting_started_mac.html)
* [Getting Started on Windows (MSVC)](https://slightech.github.io/MYNT-EYE-SDK/getting_started_win.html)
* [Getting Started on Tegra (TX1, TX2)](https://slightech.github.io/MYNT-EYE-SDK/getting_started_tegra.html)

## Archives

This section provides archived and obsolete versions of the MYNT EYE SDK.

On Linux, please download the SDK with the consistent version of GCC, because GCC 5 uses a new ABI by default (see [here](https://gcc.gnu.org/gcc-5/changes.html#libstdcxx)). You can run `gcc --version` to see your GCC version.

Here are missing things on some platforms, marked with `×`.

<table>
  <tr>
    <td rowspan="2" colspan="2">Platform</td>
    <td rowspan="2">Apps</td>
    <td colspan="2">Features</td>
  </tr>
  <tr>
    <td>CPU</td>
    <td>CUDA</td>
  </tr>
  <tr>
    <td>Tegra</td>
    <td>TX1/TX2</td>
    <td>×</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>AArch64</td>
    <td>×</td>
    <td></td>
    <td>×</td>
  </tr>
</table>

### Release 1.4

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td rowspan="2">Linux</td>
    <td rowspan="2">GCC4</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-linux-x64-gcc4-opencv-3.2.0.tar.gz">mynteye-1.4-linux-x64-gcc4-opencv-3.2.0.tar.gz</a></td>
    <td>27.37 MB</td>
    <td>3fd956808f2de50b1e88a6dc168acaec</td>
  </tr>
  <tr>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-linux-x64-gcc4-opencv-2.4.13.3.tar.gz">mynteye-1.4-linux-x64-gcc4-opencv-2.4.13.3.tar.gz</a></td>
    <td>27.37 MB</td>
    <td>00f61690fbb1a2eed4b3a0681c723b66</td>
  </tr>
  <tr>
    <td rowspan="2">Linux</td>
    <td rowspan="2">GCC5</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-linux-x64-gcc5-opencv-3.2.0.tar.gz">mynteye-1.4-linux-x64-gcc5-opencv-3.2.0.tar.gz</a></td>
    <td>27.4 MB</td>
    <td>4b3afeb551fbed0983f9f1b06eb87ff6</td>
  </tr>
  <tr>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-linux-x64-gcc5-opencv-2.4.13.3.tar.gz">mynteye-1.4-linux-x64-gcc5-opencv-2.4.13.3.tar.gz</a></td>
    <td>27.4 MB</td>
    <td>6e1db5b30280f7162a86a066e219f6a1</td>
  </tr>
  <tr>
    <td rowspan="2">macOS</td>
    <td rowspan="2"></td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-mac-x64-opencv-3.2.0.tar.gz">mynteye-1.4-mac-x64-opencv-3.2.0.tar.gz</a></td>
    <td>16.92 MB</td>
    <td>7a491ca23e66f56c4130de7993e49881</td>
  </tr>
  <tr>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-mac-x64-opencv-2.4.13.3.tar.gz">mynteye-1.4-mac-x64-opencv-2.4.13.3.tar.gz</a></td>
    <td>16.91 MB</td>
    <td>7c8a4cfd1dd1622c37419cd3797d3da9</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>MSVC</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-win-x64-opencv-3.2.0.tar.gz">mynteye-1.4-win-x64-opencv-3.2.0.tar.gz</a></td>
    <td>42.81 MB</td>
    <td>1e31c3bd2017505d77cfa7af975115c7</td>
  </tr>
  <tr>
    <td rowspan="2">Tegra</td>
    <td rowspan="2">TX1/TX2</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-tegra-aarch64-gcc5-opencv-3.2.0.tar.gz">mynteye-1.4-tegra-aarch64-gcc5-opencv-3.2.0.tar.gz</a></td>
    <td>5.41 MB</td>
    <td>bb8b8be6f941cf7c0b310e562a7f4f54</td>
  </tr>
  <tr>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.4/mynteye-1.4-tegra-aarch64-gcc5-opencv-2.4.13.1.tar.gz">mynteye-1.4-tegra-aarch64-gcc5-opencv-2.4.13.1.tar.gz</a></td>
    <td>5.42 MB</td>
    <td>e56ff71b93da527f18e7423d5ed4db1b</td>
  </tr>
</table>

### Release 1.3

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC4</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.3/mynteye-1.3-linux-x64-gcc4.tar.gz">mynteye-1.3-linux-x64-gcc4.tar.gz</a></td>
    <td>27.31 MB</td>
    <td>dad4dc41a206e31a35f382af87f0c2f9</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC5</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.3/mynteye-1.3-linux-x64-gcc5.tar.gz">mynteye-1.3-linux-x64-gcc5.tar.gz</a></td>
    <td>27.34 MB</td>
    <td>51ef7e0027a9d8ea789bd46f5e39a83c</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.3/mynteye-1.3-mac-x64.tar.gz">mynteye-1.3-mac-x64.tar.gz</a></td>
    <td>16.86 MB</td>
    <td>64a761df96b923115f3bc2d3bbd39b86</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>MSVC</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.3/mynteye-1.3-win-x64.tar.gz">mynteye-1.3-win-x64.tar.gz</a></td>
    <td>42.83 MB</td>
    <td>38608f0749eb63be562590236ed445ea</td>
  </tr>
  <tr>
    <td>Tegra</td>
    <td>TX1/TX2</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.3/mynteye-1.3-tegra-aarch64-gcc5.tar.gz">mynteye-1.3-tegra-aarch64-gcc5.tar.gz</a></td>
    <td>5.34 MB</td>
    <td>de9449fa3debf23e764e8367706b47cc</td>
  </tr>
</table>

### Release 1.2

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC4</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.2/mynteye-1.2-linux-x64-gcc4.tar.gz">mynteye-1.2-linux-x64-gcc4.tar.gz</a></td>
    <td>27.3 MB</td>
    <td>6802f5ef5b3fb8215a6cbad8489cb058</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC5</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.2/mynteye-1.2-linux-x64-gcc5.tar.gz">mynteye-1.2-linux-x64-gcc5.tar.gz</a></td>
    <td>27.33 MB</td>
    <td>b38195ea9ead0295b996dffe81009066</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.2/mynteye-1.2-mac-x64.tar.gz">mynteye-1.2-mac-x64.tar.gz</a></td>
    <td>16.84 MB</td>
    <td>825e0de83fa8c05920394827b2699b9e</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>MSVC</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.2/mynteye-1.2-win-x64.tar.gz">mynteye-1.2-win-x64.tar.gz</a></td>
    <td>42.81 MB</td>
    <td>be132fdcd9d0645389f0ba3a35445588</td>
  </tr>
  <tr>
    <td>Tegra</td>
    <td>TX1/TX2</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.2/mynteye-1.2-tegra-aarch64-gcc5.tar.gz">mynteye-1.2-tegra-aarch64-gcc5.tar.gz</a></td>
    <td>5.33 MB</td>
    <td>a65850988a9e7ce7ddcc2a7ec7160a6d</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>AArch64<br/>GCC5</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.2/mynteye-1.2-linux-aarch64-gcc5.tar.gz">mynteye-1.2-linux-aarch64-gcc5.tar.gz</a></td>
    <td>5.27 MB</td>
    <td>b07dccd6b45e9eaddf00993d3fa205cd</td>
  </tr>
</table>

### Release 1.1

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC4</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.1/mynteye-1.1-linux-x64-gcc4.tar.gz">mynteye-1.1-linux-x64-gcc4.tar.gz</a></td>
    <td>27.28 MB</td>
    <td>2733b307330fc49b4b26ae75a6abbadd</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC5</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.1/mynteye-1.1-linux-x64-gcc5.tar.gz">mynteye-1.1-linux-x64-gcc5.tar.gz</a></td>
    <td>27.32 MB</td>
    <td>e6f6cc0e223bc99ecf2ef82e83c12edf</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.1/mynteye-1.1-mac-x64.tar.gz">mynteye-1.1-mac-x64.tar.gz</a></td>
    <td>16.83 MB</td>
    <td>e2e7971d918b430545b5b73bf65c02ce</td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>MSVC</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.1/mynteye-1.1-win-x64.tar.gz">mynteye-1.1-win-x64.tar.gz</a></td>
    <td>42.81 MB</td>
    <td>a96cba813670c9ea31ae1723113ad444</td>
  </tr>
</table>

### Release 1.0

<table>
  <tr>
    <td colspan="3">Platform</td>
    <td>Package Size</td>
    <td>MD5 Checksum</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC4</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.0/mynteye-1.0-linux-x64-gcc4.tar.gz">mynteye-1.0-linux-x64-gcc4.tar.gz</a></td>
    <td>27.26 MB</td>
    <td>84184f75f5ca8970ed446abc6287bdbe</td>
  </tr>
  <tr>
    <td>Linux</td>
    <td>GCC5</td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.0/mynteye-1.0-linux-x64-gcc5.tar.gz">mynteye-1.0-linux-x64-gcc5.tar.gz</a></td>
    <td>27.22 MB</td>
    <td>efe3f9bd1e8fb9054933399d42971ce6</td>
  </tr>
  <tr>
    <td>macOS</td>
    <td></td>
    <td><a href="https://github.com/slightech/MYNT-EYE-SDK/blob/master/1.x/1.0/mynteye-1.0-mac-x64.tar.gz">mynteye-1.0-mac-x64.tar.gz</a></td>
    <td>16.82 MB</td>
    <td>e43a0b429681236134515e5add1e7702</td>
  </tr>
</table>

## Mirrors

国内镜像：[码云](https://gitee.com/mynt/MYNT-EYE-SDK)。
