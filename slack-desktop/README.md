# Disclaimer

This is for Windows.

# How to use

In order to update your slack desktop client to have a dark theme you will need to locate the ssb-interop.js file for the current version of slack that you have installed

## Where is this file?

You can find this file in the following location:

```
%localappdata%\slack
```

Once here, you will see the different verisons of slack. At the time of creating this README.md the lastest slack version is 3.4.1. Navigate down the path to the static folder as shown here:

```
app-3.4.1\resources\app.asar.unpacked\src\static
```

Or for easier access (if you have the same version):

```
%localappdata%\slack\app-3.4.1\resources\app.asar.unpacked\src\static
```

# Instructions

In this location you will find the `ssb-interop.js` file.

Copy the lines from the `ssb-interop-modifications.js` file and past them at the bottom of the original slack one.

Completely restart Slack and you should see a dark themed slack now :)
