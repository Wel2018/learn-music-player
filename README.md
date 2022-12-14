[English](README.md) | [δΈ­ζ](README-CN.md)

# Learn Music Player

<p>
<img src="https://img.shields.io/github/issues/Wel2018/learn-music-player"/>
<img src="https://img.shields.io/github/stars/Wel2018/learn-music-player"/>
<img src="https://img.shields.io/github/license/Wel2018/learn-music-player"/>
<img src="https://img.shields.io/badge/platform-linux%20%7C%20windows%20-blue"/>
<img src="https://img.shields.io/github/contributors/Wel2018/learn-music-player"/>
<img src="https://img.shields.io/github/commit-activity/m/Wel2018/learn-music-player"/>
</p>

π [Blog](https://juejin.cn/user/2594503171769720/posts)
| π [Documentation](doc/overview.md)
| π¬ [FAQ](FAQ.md)
| β [Issues](https://github.com/Wel2018/learn-music-player/issues)
| π [Roadmap](https://flowus.cn/share/fb7f5722-aedb-494c-a0e7-e4954fa05443#5eb25c4c-b971-4294-bc79-1f97155d6c62)

Create your own music App from scratch.

## π Table of Contents

- [Learn Music Player](#learn-music-player)
  - [π Table of Contents](#-table-of-contents)
  - [π» Client](#-client)
  - [β¨ Features](#-features)
  - [π§± Architecture](#-architecture)
  - [π₯ Technology Stack](#-technology-stack)
  - [βοΈ Build](#οΈ-build)
  - [π¦ Related Efforts](#-related-efforts)
  - [π Recommended References](#-recommended-references)
  - [π» Contributing](#-contributing)
  - [π License](#-license)

## π» Client 

![image](doc/assets/myui.png)

**note**: 
Due to limited personal energy, the initial focus of the project is to create *Restful API*. 
The implementation of temporary client of this project use [MrRainbowYoo/Music_Player](https://github.com/MrRainbowYoo/Music_Player) project. Besides, some high quality client implementations are list in [recommended-references](#recommended-references) section. When all API and supporting documents are completed, the client supporting the project, including Qt and Electron versions, will be provided. Specific project planning see π [roadmap](https://flowus.cn/share/fb7f5722-aedb-494c-a0e7-e4954fa05443#5eb25c4c-b971-4294-bc79-1f97155d6c62).

## β¨ Features

This project use Python, C++ server to implement the common interface in [netease-cloudmusic api](https://neteasecloudmusicapi.vercel.app/#/?id=neteasecloudmusicapi) document. Expected features are:

- Personal account, favorites, comments, etc
- Recommend playlists, singles, and MV based on users' preferences
- Provides switching between online and offline modes
- Support Docker deployment
- Provide mid-stage system to manage music playlists, MV, users, etc
- ...

For more details, see [Roadmap](https://flowus.cn/share/fb7f5722-aedb-494c-a0e7-e4954fa05443#5eb25c4c-b971-4294-bc79-1f97155d6c62). 

## π§± Architecture

![](assets/architecture.png)

## π₯ Technology Stack

- Editor: Visual Studio Code
- LanguageοΌC++, Python 
- DatabaseοΌMySQL, Redis
- Access layerοΌNginx
- ClientοΌVue.js

## βοΈ Build 

The project supports traditional builds as well as Docker deployments. For more details, see [build](build.md).

## π¦ Related Efforts

-   [Binaryify/NeteaseCloudMusicApi: η½ζδΊι³δΉ Node.js API service (github.com)](https://github.com/Binaryify/NeteaseCloudMusicApi)

## π Recommended References

- [MrRainbowYoo/Music_Player: π΅εΊδΊVueηε¨ηΊΏι³δΉζ­ζΎε¨οΌι¨εUIεθη½ζδΊι³δΉοΌζ―ζε¨ηΊΏζΌη€Ίγζ¬ι‘Ήη?δ»δΎεθε­¦δΉ γ (github.com)](https://github.com/MrRainbowYoo/Music_Player)
- [Yin-Hongwei/music-website: π§ Vue + SpringBoot + MyBatis ι³δΉη½η« (github.com)](https://github.com/Yin-Hongwei/music-website) 
- [xiaozhu188/electron-vue-cloud-music: πElectron + Vue δ»Ώη½ζδΊι³δΉwindowsε?’ζ·η«― (github.com)](https://github.com/xiaozhu188/electron-vue-cloud-music)
- [caijinyc/vue-music-webapp: A Music WebApp based on the Vue. (github.com)](https://github.com/caijinyc/vue-music-webapp)
- [SmallRuralDog/electron-vue-music: εΊδΊ electron-vue εΌεηι³δΉζ­ζΎε¨οΌηι’ζ¨‘δ»ΏQQι³δΉοΌζζ―ζ electron-vue+vue+vuex+vue-router+element- UIγζ¬’θΏstar (github.com)](https://github.com/SmallRuralDog/electron-vue-music)
- [SmallRuralDog/vue3-music: VUE3+TS εΌεηι³δΉζ­ζΎε¨οΌηι’ζ¨‘δ»ΏQQι³δΉmacε?’ζ·η«―οΌζ―ζι»ε€ζ¨‘εΌ (github.com)](https://github.com/SmallRuralDog/vue3-music)
- [sl1673495/vue-netease-music: π΅ εΊδΊ Vue2γVue-CLI3 ηι«δ»Ώη½ζδΊ mac ε?’ζ·η«―ζ­ζΎε¨οΌPCοΌ Online Music Player (github.com)](https://github.com/sl1673495/vue-netease-music)
- [SevenOutman/vue-aplayer: Easy-to-use music player for Vue 2.x (github.com)](https://github.com/SevenOutman/vue-aplayer)
- [maomao1996/Vue-mmPlayer: π΅ εΊδΊ Vue ηε¨ηΊΏι³δΉζ­ζΎε¨οΌPCοΌ Online music player (github.com)](https://github.com/maomao1996/Vue-mmPlayer)
- [qier222/YesPlayMusic: ι«ι’εΌηη¬¬δΈζΉη½ζδΊζ­ζΎε¨οΌζ―ζ Windows / macOS / Linux (github.com)](https://github.com/qier222/YesPlayMusic)
- [powerdong/Music-player: Vueι«δ»Ώη½ζδΊι³δΉ(Vueε₯ι¨ε?θ·΅)ββε¨ηΊΏι’θ§ -- ζζΆεζ­’ (github.com)](https://github.com/powerdong/Music-player)
- [fudaosheng/Vue-NeteaseCloud-WebMusicApp: Vueι«δ»Ώη½ζδΊι³δΉοΌεΊζ¬ε?η°η½ζδΊζζι³δΉγMVηΈε³εθ½οΌη°ε·²ζ΄ζ°ε°η¬¬δΊηοΌδ»η¨δΊε­¦δΉ οΌδΈι’ζθ―¦η»ζη¨γ (github.com)](https://github.com/fudaosheng/Vue-NeteaseCloud-WebMusicApp)
- [microzz/vue-music-player: π΅Vue.jsεδΈδΈͺι³δΉζ­ζΎε¨+πOne(δΈδΈͺ).A music player + One by Vue.js (github.com)](https://github.com/microzz/vue-music-player)
- [boyan01/flutter-netease-music: flutter music player application. (δ»Ώη½ζδΊι³δΉ) (github.com)](https://github.com/boyan01/flutter-netease-music)
- [ddqre12345/vue-music: cloud-music(η½ζδΊι³δΉ) (github.com)](https://github.com/ddqre12345/vue-music)
- [hua1995116/musiccloudWebapp: vuejsδ»Ώη½ζδΊι³δΉ (github.com)](https://github.com/hua1995116/musiccloudWebapp)
- [jsososo/NeteaseMusic: η½ζδΊι³δΉ & QQι³δΉ & εͺει³δΉ η¬¬δΈζΉ webη«― (ε―ζ­ζΎ vipγδΈζΆζ­ζ²) (github.com)](https://github.com/jsososo/NeteaseMusic)
- [ShanaMaid/vue-163-music: γεζ­’η»΄ζ€γη½ζδΊι³δΉwebηοΌζ―ζPCη«―εΈΈη¨εθ½οΌlocalStorageδΏε­ζ­ζΎεθ‘¨ (github.com)](https://github.com/ShanaMaid/vue-163-music)
- [lang1427/vue-typescript-music: εΊδΊ vue ε¨ε?Άζ‘Ά ι³δΉι‘Ήη?(Music project) vue+typescript ε?η° ι«δ»Ώ η½ζδΊι³δΉ η§»ε¨η«―WebApp (github.com)](https://github.com/lang1427/vue-typescript-music)
- [sanjings/music-pc: εΊδΊvue3+vite+typescriptεΌεηδ»Ώη½ζδΊι³δΉweb-pcη«― (github.com)](https://github.com/sanjings/music-pc)
- [Francis1024/NeteaseMusic: Vue-Cli 3 + Vuex + Vant UI ηη§»ε¨η«―η½ζδΊι³δΉ (github.com)](https://github.com/Francis1024/NeteaseMusic)
- [Nele7/music: π΅vue εη΄ ηΊ§θΏεmacε?’ζ·η«―η½ζδΊι³δΉ (github.com)](https://github.com/Nele7/music)
- [LaravelChen/vue-music: εΊδΊLaravel5.3+Vue2.0ηη½ζδΊι³δΉηSPAεΊη¨ (github.com)](https://github.com/LaravelChen/vue-music)
- [sunzongzheng/music: electronθ·¨εΉ³ε°ι³δΉζ­ζΎε¨οΌε―ζη½ζδΊγQQι³δΉγθΎη±³ι³δΉοΌζ―ζQQγεΎ?εγGithubη»ε½οΌδΊζ­ε; ζ―ζδΈι?ε―Όε₯ι³δΉεΉ³ε°ζ­ε](https://github.com/sunzongzheng/music) 
- β¦


## π» Contributing

Welcome all friends who are interested in Music-Player to β­ star this project. Your support is the biggest motivation for me to continue updating!
Due to my level and energy are limited, the blogs and related code may have inadequacies and errors, welcome to ask questions and discussion in β [Issues](https://github.com/Wel2018/learn-cpp-rezero/issues), also welcome to **Pull Requests** when you make sure which are not already open.

>   β  Note: Due to the consideration of music copyright and relevant laws and regulations, the relevant access code of NetEase Cloud Music has been deleted. If you find any other problems, please refer to Issues. Thank you!

## π License  

MIT License (for more details, see the [license file](LICENSE))

