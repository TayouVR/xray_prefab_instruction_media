# How to install X-Ray pussy prefab

1. Make sure you have VRCFury installed, see https://vrcfury.com/download/    
   ![image](https://user-images.githubusercontent.com/31988415/244846666-dcc675e7-0949-4fd4-8aab-4bde26fed55e.png)
2. place the prefab from this folder into your avatar in the scene   
   ![image](https://raw.githubusercontent.com/TayouVR/xray_prefab_instruction_media/main/.github/images/step2.gif)
3. unpack the outer prefab (DON'T "Unpack Prefab Completely"!!!)   
   ![image](https://raw.githubusercontent.com/TayouVR/xray_prefab_instruction_media/main/.github/images/step3.gif)
4. in the project view, select your body material and duplicate it with CTRL+D   
   ![image](https://raw.githubusercontent.com/TayouVR/xray_prefab_instruction_media/main/.github/images/step4.gif)
5. scroll down in the duplicated material to the bottom, or rendering settings (lilToon) and set the render queue to 1998   
   ![image](https://raw.githubusercontent.com/TayouVR/xray_prefab_instruction_media/main/.github/images/step5.gif)
6. on the (now unpackaged) prefab in your avatar there are 4 VRCFury toggles, 3 of which have a empty "Material" slot.   
   on those, drag your body mesh into the first slot, then drag the new duplicated body material into the second slot to the right for all three toggles.   
   ![image](https://raw.githubusercontent.com/TayouVR/xray_prefab_instruction_media/main/.github/images/step6.gif)
7. now either move the entire prefab into your armature where you want it, or add a target to the parent constraint below the VRC Fury component. (if you don't use the constraint, delete it)   
   ![image](https://raw.githubusercontent.com/TayouVR/xray_prefab_instruction_media/main/.github/images/step7.gif)

## Video Instructions
https://github.com/TayouVR/xray_prefab_instruction_media/assets/31988415/d6a03557-a796-435d-8102-5ebf83a90d44
