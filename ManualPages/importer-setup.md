<p align=center><img src="../images/rig_renderfiles/Importer_Base.png" width="300" height="300"></p>

Importer Wizard can be used to import any character at any location of the scene. The character root will also follow how the importer's orientation.

<p align=center><img src="../images/importer-setup/0001.png"></p>

1. Character Name
  > It is the character name you can assign to a character model before importing. It will reflect to the Bone, Mesh, Cape, Face, and Object Binder names.

2. Skin Path
  > It is the file path of your skin. In the importer model, the left side will be colored Green if it is acceptable, or the default will be used.

3. SSS / Subsurface Scattering File Path (Only in UCR 2.2)
  > It is the file path for the mask used by Subsurface Scattering. Usually the same as the skin file but all non-skin parts are removed.
  
<p align=center><img src="../images/importer-setup/0003.png"></p>
  
4. V3 Type (UCR 2.2) / V1 Type (UCR 1.3)
  > It is the type of face you want to use.
  > - Square Mouth and Rounded Square Mouth for UCR 2.2
  > - Male and Female Face Types for UCR 1.3 (Have oval and squared mouth modes via Q-Controls)
  
5. Character Type
  > Chooses whether the character will have a Steve 4px Arms or Alex 3px Arms
  
6. Mesh Type (UCR 2.2 - 3 Types / UCR 1.3 - 2 Types)
  > Chooses which type of mesh the character will have
  > - UCR 2.2 have Freesize Mesh (Unextrudable), High-Poly Mesh (64x64), and Extra High Poly Mesh (128x128)
  > - UCR 1.3 have LowPoly Mesh (Unextrudable, only used as placeholder character), and Normal Mesh (64x64)
  
7. Include Bones
  > This will dictate if you want to import the default bones for your character of choice. It can be disabled if you plan to bind your bones which has been pre-posed.
  
8. Cape Type
  > Chooses what cape you want to give your character.
  > - Regular Cape - the usual cape used in Minecraft
  > - Optifine Cape - the one sometimes being used on servers. Uses banner texture most of the time.

9. Importer Code
 > - Current Code is a copy-able code which you can use in other importers present on the scene, or save in your notes so that you just need to type the code in the New Code field that sets the value of each settings in the Importer (Excluding skin and SSS data).
 
10. Run
  > When all is valid, pressing this button will import your character. Otherwise it will do nothing.
