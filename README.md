

Other Languages: [繁體中文](https://github.com/laplamgor/kantai3d/blob/main/README.zh-Hant.md) [日本語](https://github.com/laplamgor/kantai3d/blob/main/README.ja.md)

> Related Repositories:
> * Install Option A (PC Chrome): [Chrome Extension](https://github.com/laplamgor/kantai3d-chrome-extension)
> * Install Option B (PC [poi](https://github.com/poooi/poi)): [Poi Viewer Plugin](https://github.com/laplamgor/kantai3d-poi-plugin)
> * Install Option C (PC Proxy): [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher)
> * Install Option D (Android): [GotoBrowser (2.6 or newer)](https://github.com/antest1/GotoBrowser) - Kantai3D available in its setting page
> * For Contributors: [Depth Map Library](https://github.com/laplamgor/kantai3d-depth-maps)
> * For Contributors (in Beta): [Web-based Depth Map Editor](https://github.com/laplamgor/kantai3d-online-editor)


# Kantai3D
Kantai3D is a third-party mod for Kancolle - Kantai Collection. It brings 3D-like effects and jiggle physics to (some of) your secretaries. 


### 3D effect:

![0463_7319_grmdtyheocuc](https://user-images.githubusercontent.com/11514317/96752931-b8a0c980-1401-11eb-8e42-1b02b336435d.gif) ![ezgif-3-10400017ed1e](https://user-images.githubusercontent.com/11514317/97005334-e0fb0600-1570-11eb-97b3-85896c1a463b.gif)

### Jiggle physics (adding since v2.0):

![ezgif-7-39734d119569](https://user-images.githubusercontent.com/11514317/134775124-3ceb0bc6-a425-47c9-8219-5fb181767ade.gif)

It is NOT Live2D. It is parallax occlusion mapping (POM) rendering technique which uses a depth map to simulate occlusion of 3D lightray. 3D AAA game usually use this technique on walls and floor for extra bump visual effects.


# [Supported CGs](https://github.com/users/laplamgor/projects/1#column-10244994)

Drawing depth maps is very time consuming and the number of supported CGs is slowing increasing. Please consider contributing depth maps for your favorite ships.

p.s. Currently Kantai3D does not support any medium damaged CG.

# Installation

Currently Kantai3D is only available for limited platforms and there are a few options to install it.

For PC Chrome user, please check out the [Chrome Extension](https://github.com/laplamgor/kantai3d-chrome-extension).

For PC [poi](https://github.com/poooi/poi) user, please install the [plugin](https://github.com/laplamgor/kantai3d-chrome-extension) within the browser plugin manager.

For other PC user, you can use install throught [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher).
The KCCP patcher requires [KC Cache Proxy](https://github.com/Tibowl/KCCacheProxy). 

For Android user, you can use [GotoBrowser](https://github.com/antest1/GotoBrowser) which is third party Kancolle browser app with built-in Kantai3D (as an experienmental feature).

# Contribute your own depth Map

In long term, I would like this project to be fan-based. It definitely needs more than one busy poor man to draw all depth maps for 200+ ships and 500+ CGs.

I have created an [online editor](https://github.com/laplamgor/kantai3d-online-editor) to draw depth map.

You can create depth map for your favorite ship CG. (CG base image will not not provided by me due to copyright.)

## Pull Request or Email

If you want your depth map to work with Kantai3D, just do a pull request [on this repo](https://github.com/laplamgor/kantai3d-depth-maps).

Or if you are not familiar with Github, you can also just email me your work.


# Disclaimer
Kantai3D is not an officially approved program. Using it may be aganist the Terms of Service of DMM.

Kantai3D modifies your local game client (main.js) in order to achieve the visual effects but does not modify any ingame API request and response. It does not affect your noraml gameplay or game balance. 

Please use it at your own risk. 


This mod alone, does not include any data from the origin game. All depth maps used are also 100% hand-drawn. 

If you have any questions or queries, please contact me at laplamgor@gmail.com
