# Nine-Patch Cordova for Android Test

See [LICENSE][] for license terms and conditions.

This application is very simple. It includes some sample nine-patch
splash screen images to show you how a nine-patch image can be used to
create a splash screen that will not distort on different Android
devices. The center "square" in each test image is marked as
"non-scalable" and will retain its original dimensions. The areas
outside the square are marked as scalable and will distort.

Two sets of images are provided in the project, the original PNG images
and the nine-patch PNG (9.png) images. The nine-patch images were
created using the Android `draw9patch` tool, but any PNG image editor
that can mark pixels in a transparent color can be used. If you do not
use the Android `draw9patch` tool to edit your images please make note
of the image sizes.

For reference, please see these articles:

-   <http://radleymarx.com/blog/simple-guide-to-9-patch/>

-   <http://iphonedevlog.wordpress.com/2013/07/02/creating-and-installing-a-splash-screen-for-android-using-eclipse-and-phonegap/>

-   <http://developer.android.com/guide/topics/graphics/2d-graphics.html#nine-patch>

-   <http://developer.android.com/tools/help/draw9patch.html>

This project is ready to use:

-   clone this project from github onto your workstation

-   "open" (don't "import") the local clone in the Intel XDK

-   build the project and install on an Android device

Pressing the "show splash screen" button will cause the splash screen to
be displayed for \~five seconds. Run the app on a variety of devices to
see how different screen sizes and aspect ratios change the splash
screen.

> NOTE: You can run this app in the Emulator or using the Debug and Test
> tabs, but you will not see the custom splash screens. You must build
> and install the app on an Android device to see the custom splash
> screen.

This project was created using version 1199 of the Intel XDK.

  [LICENSE]: LICENSE
