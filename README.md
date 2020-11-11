# Fission Drop

This is a simple, proof-of-concept AppleScript "droplet" app that uses Fission to publicly share files.

## Pre-requisite:

Make sure you have [Fission CLI installed](https://guide.fission.codes/developers/installation) and [Setup](https://guide.fission.codes/developers/getting-started).

## Usage

To create the app:

1. Download FissionDrop.applescript and open it in Script Editor (on macOS).
1. Select File > Export ... and select "Application" as the "File format". This will create FissionDrop.app.
1. Simply drop an image on the app icon and when the upload is complete, the full url will be on your clipboard.

_Note_: The first time you run the application, it will prompt for Finder permissions (if you're on Catalina or newer) and then prompt you to select a folder (or create). Images will be moved to this folder and published online.


## Make changes!

With a few tweaks, this script can be used as an Automator folder action (i.e. publish the contents of a folder)
