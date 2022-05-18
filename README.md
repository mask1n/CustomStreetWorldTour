# Custom Street World Tour

![](CustomStreetWorldTourTitle.webp)

Custom Street World Tour is an easy-to-install map pack for Fortune Street and Boom Street containing over a hundred custom boards from the [Custom Street Board Repository](https://fortunestreetmodding.github.io/maps), some including custom music and backgrounds.

## Latest Stable Release

**Version 1.0 is available now! This is a tested and stable release with 135 new boards, as well as the inclusion of a console-friendly version. See releases on the right to download.**

## Latest Development Build

The development build contains all the latest boards and changes to CSWT, but it is not as thoroughly tested as the stable releases and lacks support for playing on console.

### For Genral Users

1. Download [setup.bat](Setup/setup.bat) (Windows) or [setup.sh](Setup/setup.sh) (Unix) (on the page, right click 'Raw' and save linked content)
2. Put the `setup.bat`/`setup.sh` and a vanilla Fortune Street or Boom Street iso/wbfs into a new empty directory
3. Run the `setup.bat`/`setup.sh` to set up the needed tools automatically
4. Run the `CustomStreetWorldTour/build.bat` (Windows) or `CustomStreetWorldTour/build.sh` (Unix) to build Custom Street World Tour

### For Developers

- You need to have [git](https://git-scm.com/) installed
- You need to have [python](https://www.python.org/) installed (at least version 3.9)
  - During installation of python make sure to check the checkbox "Add Python to PATH"
- You need to have copy of Fortune Street or Boom Street (.iso or .wbfs). This file needs to be in the same directory as this script. Also make sure there is only one original iso/wbfs in this directory.

#### Getting Started for Developers

1. Clone this repository using git. Do not forget to clone submodules as well.
2. Install the needed python packages using `python -m pip install --requirement requirements.txt`
3. Put a vanilla Fortune Street or Boom Street (.iso or .wbfs) into the same path. The iso image should also not contain any special characters and no spaces.
4. Start the `build.bat` (windows) or `build.sh` (unix) file to run the build.

#### [For any questions or feedback, please visit our Discord!](https://discord.gg/DE9Hn7T)
