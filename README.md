

Other Languages: [繁體中文](https://github.com/laplamgor/kantai3d/blob/main/README.zh-Hant.md) [日本語](https://github.com/laplamgor/kantai3d/blob/main/README.ja.md)

> Related Repositories:
> * Install Option A (PC Chrome): [Chrome Extension](https://github.com/laplamgor/kantai3d-chrome-extension)
> * Install Option B (PC [poi](https://github.com/poooi/poi)): [Poi Viewer Plugin](https://github.com/laplamgor/kantai3d-poi-plugin)
> * ~~Install Option C (PC Proxy): [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher)~~ (discontinued)
> * Install Option D (Android): [GotoBrowser (2.6 or newer)](https://github.com/antest1/GotoBrowser) - Kantai3D available in its setting page
> * For Contributors: [Custom Depth Map Library](https://github.com/laplamgor/kantai3d-depth-maps)
> * For Contributors (in Beta): [Web-based Depth Map Editor](https://github.com/laplamgor/kantai3d-online-editor)
> * [Depth Map Generator](https://github.com/laplamgor/kantai3d-depth-gen) (new!!!)


# Kantai3D
Kantai3D is a third-party mod for Kancolle - Kantai Collection. It brings 3D-like effects and jiggle physics to your secretaries. 


### 1. 3D effect:
![ezgif-5-acf95d0da0e8](https://user-images.githubusercontent.com/11514317/144702625-fcf94f94-adc7-4741-b098-976cf757c556.gif)
![ezgif-5-651e1f9db9ac](https://user-images.githubusercontent.com/11514317/144702627-36642582-4b92-4af7-8c58-613d7acca56e.gif)

It is NOT Live2D. It is a parallax occlusion mapping (POM) rendering technique that uses a depth map to simulate the occlusion of 3D light rays. 3D AAA games usually use this technique on walls and floors for extra bump visual effects.

### 2. Jiggle physics (Since v2.0):

![ezgif-7-39734d119569](https://user-images.githubusercontent.com/11514317/134775124-3ceb0bc6-a425-47c9-8219-5fb181767ade.gif)
![ezgif-5-7d7de6bb4a51](https://user-images.githubusercontent.com/11514317/144702132-9954f9ad-f43a-41f3-8db9-6eceda3ca156.gif)

### 3. In-game UI toggle (Since v3.0):

![download](https://user-images.githubusercontent.com/11514317/166011636-9b9a93cc-5786-4983-91a1-963da70ce514.png)

# Supported CGs

There are two types of depth maps: 
1. [Custom painted depth maps](https://github.com/users/laplamgor/projects/3/views/1)
   - Only a few ships have custom depth maps currently. 
   - Custom depth maps are higher quality and may contain jiggle effects.
2. [AI-generated depth maps (Depth Pro)](https://github.com/laplamgor/kantai3d-depth-gen)
   - They cover almost every ship CG without a custom map.
   - 3D effect quality is slightly worse than custom maps.
   - They also support jiggle effects.

Drawing custom depth maps is very time-consuming, and the number of custom-supported CGs is slowly increasing. Please consider contributing depth maps for your favourite ships.

# Installation

Currently, Kantai3D is only available for a limited platforms, and there are a few options to install it.

For PC Chrome users, please check out the [Chrome Extension](https://github.com/laplamgor/kantai3d-chrome-extension).

For PC [poi](https://github.com/poooi/poi) users, please install the [plugin](https://github.com/laplamgor/kantai3d-chrome-extension) within the browser plugin manager.

~~For other PC users, you can install it through [KanColle Cache Proxy Patcher](https://github.com/laplamgor/kantai3d-kccp-patcher).~~
~~The KCCP patcher requires [KC Cache Proxy](https://github.com/Tibowl/KCCacheProxy).~~

For Android users, you can use [GotoBrowser](https://github.com/antest1/GotoBrowser), which is a third-party Kancolle browser app with built-in Kantai3D (as an experimental feature).

# Contribute your custom depth Map

Originally, I wanted this project to be fan-based and hoped some users would contribute their depth maps. 

By far, there are only a few contributions over the years, while new AI models generate more usable maps.

Human contribution does not matter anymore, but you can still use my tools for fun or non-game CGs.

I have created an [online editor](https://github.com/laplamgor/kantai3d-online-editor) to draw a custom depth map.

You can create a custom depth map for your favourite ship CG. (CG base image will not be provided by me due to copyright.)

You can also email me for more details.

## Pull Request or Email

If you want your depth map to work with Kantai3D, just do a pull request [on this repo](https://github.com/laplamgor/kantai3d-depth-maps).

Or if you are not familiar with GitHub, you can also just email me your work.


# Disclaimers
Kantai3D is not an officially approved program. Using it may be against the Terms of Service of DMM.

Kantai3D modifies your local game client (main.js) to achieve the visual effects, but does not modify any in-game API requests and responses. It does not affect your normal gameplay or game balance. 

Please use it at your own risk. 


This mod alone does not include any data from the original game. All custom depth maps used are 100% hand-drawn. AI-generated results are, however, not included in the scope of this open-source project due to potential copyright issues.

If you have any questions or queries, please contact me at laplamgor@gmail.com
