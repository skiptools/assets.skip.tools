Generating screenshot frames for showcase elements (e.g., "TextEditor"):

1. Run Showcase in iPhone 14 Simulator, navigate to TextEditorPlayground
2. Save light screenshot (CMD-S), rename to TextEditor-iphone-light.png
3. Switch to darm mode (CMD-SHIFT-A) and save screenshot, rename to TextEditor-iphone-dark.png
4. Run Showcase on Pixel 5 Enumator, navigate to TextEditorPlayground
5. Save light screenshot (CMD-S), rename to TextEditor-android-light.png
6. Switch to darm mode (drag down control center) and save screenshot, rename to TextEditor-android-dark.png
7. Install fastlane (`brew install fastlane`)
8. Create framed versions for Android: fastlane frameit android --resume
9. Create framed versions for iPhone: fastlane frameit iphone --resume

This will generate screenshots with the _framed.png suffix:

    468K TextEditor-iphone-light.png
    462K TextEditor-iphone-dark.png
    269K TextEditor-android-light.png
    271K TextEditor-android-dark.png
    564K TextEditor-android-dark_framed.png
    563K TextEditor-android-light_framed.png
    633K TextEditor-iphone-dark_framed.png
    645K TextEditor-iphone-light_framed.png

Commit and push to the https://github.com/skiptools/assets.skip.tools.git repo

Then you can reference the screens from the components page, like:

http://assets.skip.tools/showcase/TextEditor-android-light_framed.png



