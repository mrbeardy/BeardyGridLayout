# Beardy's Grid Layout Group

This package fixes an issue in the UGUI Grid Layout Group where child elements
are not properly aligned after they wrap around.

## Known Issues

The original requirement for this was to fix the issue outlined above, however since the Grid
Layout Group component supports so many scenarios, the code has issues with certain settings.

  -  Start Axis: Horizontal, Start Corner: Upper Right
  -  Start Axis: Horizontal, Start Corner: Lower Right
  -  Start Axis: Vertical, Start Corner: Lower Left (With certain child alignments)
  -  Start Axis: Vertical, Start Corner: Lower Right (With certain child alignments)

If you'd like to try and fix these issues, pull requests are welcome!

## Using

For the most part, this should work exactly like the built-in UGUI Grid Layout Group Component.

## Installing

### Via Package Manager (with git)

In the Package Manager, click the plus in the top left corner and choose 'Add package from git URL'
and use `git@github.com:mrbeardy/BeardyGridLayout.git` in the box.

### Via Package Manager (with filesystem)

First download [a zip of the repository](https://github.com/mrbeardy/BeardyGridLayout/archive/main.zip) and unzip it.

Then, in the Package Manager, click the plus in the top left corner and choose 'Add package from disk'
and navigate to the folder you unzipped earlier and select the `package.json` file.

### Via .unitypackage

Visit the releases tab and download the latest .unitypackage, then drag that into the project window in Unity.