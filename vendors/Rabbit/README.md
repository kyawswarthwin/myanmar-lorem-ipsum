# Rabbit

![Logo](./rabbit_100.png)

**Another Zawgyi <=> Unicode Converter**

## Info

Zawgyi to Unicode has been written in [2011](https://github.com/saturngod/ZG2Uni_JS/commits/master). Now, unicode to zawgyi has been finished.

### Why another converter ?

When I was writting [ZG2uni](https://github.com/saturngod/ZG2Uni_JS/) , [Parabaik](https://github.com/ngwestar/parabaik) was not opensource. At that time, I need to use for [MYSTERY ZILLION](http://www.mysteryzillion.org) for converting the whole database to Unicode. So, I wrote ZG2Uni (of course , it has some bugs and some rule missing). 

For Unicode to zawgyi , ~~Parabaik is the GPL license and cannot use in iOS app and Android App~~ Parabaik is the LGPL license. So, decided to write new one with **WTFPL license**.

> I cannot promise , it's correct 100% after converting.

> If you are not using in app or program and just for converting the text , please use [Parabaik](https://github.com/ngwestar/parabaik)

### Demo

- [Web](http://saturngod.github.io/Rabbit/)
- [Android](https://play.google.com/store/apps/details?id=com.comquas.rabbitzawgyiunicodeconverter)


## Build

All the rule are under `source/rule` folder

All the langue template and compile script are under `source/lang` folder

To Build 

```
cd source
node build.js
```

You can get build result under the `output` folder.
