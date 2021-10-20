# Unique-Victory-Result-Updated-
##Original Author
- Coolsonickirby

##Updated Author
- Puli2004
- Wuboy

#Copied from Coolsonickirby Unique-Victory Updated by Puli2004 and Wuboy. Edited by Puli2004
#Discord:Puli2004#8377 WuBoy#0238
## Prerequisites
- [ARCropolis 1.1.3 or higher](https://github.com/Raytwo/ARCropolis/releases/latest)
- [Skyline (Should come with ARCropolis)](https://github.com/skyline-dev/skyline/releases/tag/beta)
- [Smasline_hook](https://github.com/blu-dev/smashline_hook/releases/tag/1.1.1)
- [NRO Hook 0.2.0](https://github.com/ultimate-research/nro-hook-plugin/releases/tag/v0.2.0)

## Setup
Download the latest version of this plugin and put it in:
`sd:/atmosphere/contents/01006A800016E000/romfs/skyline/plugins`

## Usage
Create a folder called `VictoryStage` in the following path:
`sd:/atmosphere/contents/01006A800016E000/romfs/`

Inside that folder, create a config file called `config.toml` and put the following information in it:
```toml
[<Character Code Name>]
default="<Folder in VictoryStage>"
c0X="<Another Folder in VictoryStage>" # X can be a number from 0 to 7, and there can be multiple (for ex, c01, c03, etc...)
```
Now you can create folders in `VictoryStage` then put your files in them. So for example, it'd look something like this:
`sd:/atmosphere/contents/01006A800016E000/romfs/VictoryStage/<Some Folder>/<arc path>`

An example of a config file:
```toml
[mario]
default="bob"
c01="whomp"
c06="castle"
[younglink]
default="younglink"
c01="bob"
[koopa]
default="bowser"
c01="younglink"
[peach]
default="castle"
c01="bob"
[sonic]
default="Brawl"
```

## Reason for crash

-All Default stage files are missing

-Too many tris are getting loaded

-Switch went to sleepmode due to runtime process stopping 

## Fixes

-Put all Default stage files in VictoryStage

-Lower your maps tris and edit it

-This is not on our end. Really we think it might be nro_hook or smashline_hook causing this problem. Not the mod. 
```
Also please do not go to the developers and ask them to fix it. We really don't know as this mod only replaces.
It could be in their end or it could be from our end.
We don't know as the old version never had this problem till Sora came out.
We should be thankful that it works and this mod would not be possible without them working on these tools we use.
```
## If any problems report it and I'll see what happening

##If anyone doesn't know their code names go here
-[Charater Code names](https://gamebanana.com/tools/6934)
