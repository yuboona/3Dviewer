# 3Dviewer

3D模型查看器
----

## What This Is

This is a small app created by js for viewing 3D model files like .mtl .obj .  

**3D Reconstruction and 3D modeling** is really popular now.**Pix4D, autodesk3D and 3Dcloud** are really convenient tools to reconstrut 3D models from photos.But some Opensource software for reconstructions like [OpenDroneMap][1], it **don't supply a tool to view the reconstruction files**.

So I collected a [JS 3Dviewer App][2] from github, then using the [Electron][3] to make a native App for linux. It's small but useful.

[1]: https://github.com/OpenDroneMap/OpenDroneMap
[2]: https://github.com/kovacsv/Online3DViewer
[3]: https://electronjs.org/

## How to use

In Terminal, use following command lines:

```shell
    $ cd /path/to/your/location
    $ git clone git@github.com:yuboona/3Dviewer.git

    # start install
    $ cd 3Dviewer

    # make sure that you have install the Node and npm
    # Or you need to install them by "$ sudo apt install nodejs & npm
    $ npm install

    # start the app
    $ npm start

```

If you want to use this app like a native app, you can search the [Electron][3] documentation.

## What's the [Electron][3]

It's a framwork to build cross platform desktop apps with JavaScript, HTML, and CSS.

You can use any nodejs code in this framwork. [VSCode][4] is build by it.

[4]: https://electronjs.org/apps/visual-studio-code
