# Merge log

Scroll down for the original README.md!

Base revision: 9afd58cec2387777bf32e08f52a0871f1132c7da

|Pull Request|Commit|Title|Author|Merged?|
|----|----|----|----|----|
|[6](https://github.com/citra-emu/citra-canary/pull/6)|[d9c3e53](https://github.com/citra-emu/citra-canary/pull/6/files/)|Canary Base (MinGW Test)|[liushuyu](https://github.com/liushuyu)|Yes|
|[5216](https://github.com/citra-emu/citra/pull/5216)|[cfb2cab](https://github.com/citra-emu/citra/pull/5216/files/)|video_core: Attempt to remove the accurate multiplication setting|[BreadFish64](https://github.com/BreadFish64)|Yes|
|[5214](https://github.com/citra-emu/citra/pull/5214)|[23ec772](https://github.com/citra-emu/citra/pull/5214/files/)|Update dynarmic|[hamish-milne](https://github.com/hamish-milne)|Yes|
|[5213](https://github.com/citra-emu/citra/pull/5213)|[783e7af](https://github.com/citra-emu/citra/pull/5213/files/)|Services/FS: Stubbed GetSdmcArchiveResource and GetNandArchiveResource.|[Subv](https://github.com/Subv)|Yes|
|[5195](https://github.com/citra-emu/citra/pull/5195)|[0f31043](https://github.com/citra-emu/citra/pull/5195/files/)|[WIP] Add sample rate field to AAC decoder|[xperia64](https://github.com/xperia64)|Yes|
|[5174](https://github.com/citra-emu/citra/pull/5174)|[1783d96](https://github.com/citra-emu/citra/pull/5174/files/)|Port yuzu-emu/yuzu#3268: "GUI: Deadzone controls for sdl engine at configuration input"|[FearlessTobi](https://github.com/FearlessTobi)|Yes|
|[5133](https://github.com/citra-emu/citra/pull/5133)|[650d50c](https://github.com/citra-emu/citra/pull/5133/files/)|input_common/udp: Port various changes from yuzu|[FearlessTobi](https://github.com/FearlessTobi)|Yes|
|[5130](https://github.com/citra-emu/citra/pull/5130)|[ed51f06](https://github.com/citra-emu/citra/pull/5130/files/)|Show an error if CIA contend is encrypted|[B3n30](https://github.com/B3n30)|Yes|
|[5108](https://github.com/citra-emu/citra/pull/5108)|[ab76b0b](https://github.com/citra-emu/citra/pull/5108/files/)|Load NCCHSecure2 keyX from native firm|[B3n30](https://github.com/B3n30)|Yes|
|[4908](https://github.com/citra-emu/citra/pull/4908)|[d6c8422](https://github.com/citra-emu/citra/pull/4908/files/)|Save states|[hamish-milne](https://github.com/hamish-milne)|Yes|


End of merge log. You can find the original README.md below the break.

------

**BEFORE FILING AN ISSUE, READ THE RELEVANT SECTION IN THE [CONTRIBUTING](https://github.com/citra-emu/citra/wiki/Contributing#reporting-issues) FILE!!!**

Citra
==============
[![Travis CI Build Status](https://travis-ci.com/citra-emu/citra.svg?branch=master)](https://travis-ci.com/citra-emu/citra)
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/sdf1o4kh3g1e68m9?svg=true)](https://ci.appveyor.com/project/bunnei/citra)
[![Bitrise CI Build Status](https://app.bitrise.io/app/4ccd8e5720f0d13b/status.svg?token=H32TmbCwxb3OQ-M66KbAyw&branch=master)](https://app.bitrise.io/app/4ccd8e5720f0d13b)
[![Discord](https://img.shields.io/discord/220740965957107713?color=%237289DA&label=Citra&logo=discord&logoColor=white)](https://discord.gg/FAXfZV9)

Citra is an experimental open-source Nintendo 3DS emulator/debugger written in C++. It is written with portability in mind, with builds actively maintained for Windows, Linux and macOS.

Citra emulates a subset of 3DS hardware and therefore is useful for running/debugging homebrew applications, and it is also able to run many commercial games! Some of these do not run at a playable state, but we are working every day to advance the project forward. (Playable here means compatibility of at least "Okay" on our [game compatibility list](https://citra-emu.org/game).)

Citra is licensed under the GPLv2 (or any later version). Refer to the license.txt file included. Please read the [FAQ](https://citra-emu.org/wiki/faq/) before getting started with the project.

Check out our [website](https://citra-emu.org/)!

Need help? Check out our [asking for help](https://citra-emu.org/help/reference/asking/) guide.

For development discussion, please join us on our [Discord server](https://citra-emu.org/discord/) or at #citra-dev on freenode.

### Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/citra-emu/citra) is hosted.

If you want to contribute please take a look at the [Contributor's Guide](https://github.com/citra-emu/citra/wiki/Contributing) and [Developer Information](https://github.com/citra-emu/citra/wiki/Developer-Information). You should also contact any of the developers in the forum in order to know about the current state of the emulator because the [TODO list](https://docs.google.com/document/d/1SWIop0uBI9IW8VGg97TAtoT_CHNoP42FzYmvG1F4QDA) isn't maintained anymore.

If you want to contribute to the user interface translation, please checkout [citra project on transifex](https://www.transifex.com/citra/citra). We centralize the translation work there, and periodically upstream translation.

### Building

* __Windows__: [Windows Build](https://github.com/citra-emu/citra/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/citra-emu/citra/wiki/Building-For-Linux)
* __macOS__: [macOS Build](https://github.com/citra-emu/citra/wiki/Building-for-macOS)


### Support
We happily accept monetary donations or donated games and hardware. Please see our [donations page](https://citra-emu.org/donate/) for more information on how you can contribute to Citra. Any donations received will go towards things like:
* 3DS consoles for developers to explore the hardware
* 3DS games for testing
* Any equipment required for homebrew
* Infrastructure setup

We also more than gladly accept used 3DS consoles! If you would like to give yours away, don't hesitate to join our [Discord server](https://citra-emu.org/discord/) and talk to bunnei.
