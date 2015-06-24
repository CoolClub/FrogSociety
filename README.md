## Building the Project

### Windows
- You will need Python 2.7, Visual Studio 2013, and a git shell installed on your computer (I recommend cygwin).

1. Clone this repository with `git clone https://github.com/CoolClub/FrogSociety` into the directory of your choice.
2. Navigate into the `FrogSociety` directory with `cd FrogSociety` and run `git submodule update --init`. Note that before you run this command, the folders CorvusCore, cocos2d, and Resources are all empty folders. This command initializes them from other repositories. So in essence each folder may be treated as its own repository.
3. Navigate to the `cocos2d` folder with `cd cocos2d` and run `python download_deps.py`. This will download third party libraries for cocos2d. When it is finished, you may either choose to keep the downloaded zip file for future use or delete it. It doesn't matter which you choose.
4. Open FrogSociety/proj.win32/FrogSociety.sln in Visual Studio. Check to see if any project are unloaded in the Solution Explorer. For each one that is, reload it by right clicking and selecting `Reload`.
5. Select `Build > Build Solution`. This will build the project.
6. Select `Local Windows Debugger` to run the game!
