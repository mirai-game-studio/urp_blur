# urp_planeblur_fakeinterior
Unity URP - Blurred UI Material
Demo

Can not get blurred/translucent UI elements working?
This is simple, modified UI shader that blurs geometry.
Remember to enable Opaque texture either in Camera Inspector for camera or in Pipeline asset
![image](https://github.com/mirai-game-studio/urp_planeblur_fakeinterior/assets/91862765/f38b7676-2934-462d-bf38-ca615d4f9216)

Note:
-Objects are blured without post processing applied to them.
-This shader ignores transparent objects and can not stack, meaning it can not blur UI or text underneath it.

These functionalities might be added later.
