
# Firmwares

About how to upgrade firmware, please see [Tutorials](https://slightech.github.io/MYNT-EYE-SDK/tutorials.html).

<table>
  <tr>
    <td>Name</td>
    <td>Version</td>
    <td>Size</td>
    <td>MD5</td>
  </tr>
  <tr>
    <td>mynteye_0102_1708101513.img</td>
    <td>0102</td>
    <td>131.59 KB</td>
    <td>86ef4069eee6b96bf5325cae8809b904</td>
  </tr>
  <tr>
    <td>mynteye_0101_1706151738.img</td>
    <td>0101</td>
    <td>132.53 KB</td>
    <td>49041624e6dca608e0c6610a5ba16a21</td>
  </tr>
</table>

## Release Notes

### 0102

* Add the adaptability to ambient light, such as indoor and outdoor.
    - The camera will dynamic balance the brightness according to the brightness of ambient light.

**Known Situations**

* If the camera faces to a flicker light, the images may flicker too.
* If the camera focuses on a strong light indoor, the images will be dark in whole.
* For synchronizing brightness of left and right images, the right camera is the main one to detect ambient light, whose dynamic balance will influence the left one.

### 0101

* Initial release.
