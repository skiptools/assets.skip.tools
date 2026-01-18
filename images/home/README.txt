Generating screenshot frames:

Install fastlane (`brew install fastlane`), then
setup frameit: `fastlane frameit download_frames`.

See: https://docs.fastlane.tools/actions/frameit/#frameit

Take screenshots with one of the supported emulator sizes:

  https://github.com/fastlane/fastlane/blob/master/frameit/lib/frameit/device_types.rb

In a screenshots folder, run:

  fastlane frameit android --resume
  fastlane frameit --resume

This will generate screenshots with the _framed.png suffix.


