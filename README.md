# urp_planeblur_fakeinterior
Unity URP - Blurred UI Material
Can not get blurred/translucent UI elements working?
This is simple, modified UI shader that blurs geometry.
Remember to enable Opaque texture either in Camera Inspector for camera or in Pipeline asset
![image](https://github.com/mirai-game-studio/urp_planeblur_fakeinterior/assets/91862765/f38b7676-2934-462d-bf38-ca615d4f9216)

Note:
-Objects are blured without post processing applied to them.
-This shader ignores transparent objects and can not stack, meaning it can not blur UI or text underneath it.

These functionalities might be added later.


Fake Interiors
Made with Amplify Shader Editor, the Fake Interiors shader provides a way to render simple interior areas without the use of additional geometry using a set of floor, ceiling, props, and wall textures. Fully customizable, it's a reusable and lightweight effect that adds instant depth to your assets.


![image](https://github.com/mirai-game-studio/urp_planeblur_fakeinterior/assets/91862765/bb028260-b738-423e-b955-a14c65622d03)

Features
• NEW: Converted examples to HDRP/URP
• Flexible Room control
• Facade + Smoothness
• Prop Layer
• Custom Room and Prop Textures
• Room Brightness and Tint control
• Fully editable using Amplify Shader Editor

The Fake Interiors shader works with almost any type of object but user input is required as you will have to adjust room division, texture tile, and offset values in order to best fit your assets. The technique is ideally suited for environment or background objects. Dark rooms work best as they bring out environment reflections instead of driving attention to the simple interior textures.
