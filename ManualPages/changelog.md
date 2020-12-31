----------
Build 0083

Bone Set Updates:
- Fixed Shoulder Movement Bug
- Added more controller types (for arms)
- Made FK/IK Switches animatable
- Fixed FK/IK Behavior on controllers
- Hidden developer userdata groups

Facial Rig Updates
- Fixed Central Pupil Controller behavior
- Hidden some developer userdata groups
- Fixed the lag on teeth
- Made teeth modular (You can now customize your teeth using the included Teeth Module on the rig)
- Locked the spline borders on the Qube's Q-Adapter
- Fixed layer name generation

Mesh Set Updates:
- Fixed Squash and Stretch on head.
- Included a system on the mesh so Add-on Fingers can be compatible and to auto-adjust to how many pixels the fingers add-on will take.

UCR Help Block Updates:
- Updated the web opener. Now works in all versions!

Importer Updates:
- You can now name your character before importing!
- Removed most of the lag.
- New Interface! It's not a cube anymore though...

Other Updates:
- Included an Eyebrow, Eyelid, and Teeth set. Linkable to Head Rig.

----------
Build 0084

Importer Updates:
- Fixed bad lines of codes that produces Index Out of Range errors (related to Skin and SSS texture verification when you go over 64x64

UCR Help Block Updates:
- Updated the web url on it. Also updated the node that opens the url.

ObjectBinder Updates:
- Added the missing part of code which causes objects to not initialize position and rotation properly relative to the binder.

----------
Build 0085

Importer Updates:
- Updated importer script to support the updated mesh system.
- Fixed visual error with the leg part.

Bone Updates:
- Removed force rotation lock bug on both Shoulder Controllers for Full FK Mode

Mesh Updates:
- Merged Steve and Alex mesh. Mesh also will now follow the bone position.

Cape Updates:
- Rotated the cape so the front face actually faces the right direction.

----------
Build 0086

Bone Updates:
- Fixed Local IK Bug produced by IK Tag failing to update for arms.

----------
Build 0087
- Fixed missing objects (Fingers, Capes, and Importer)

----------
Build 0088

Importer Updates:
- Importer Core have syntax updates to match import settings.
- Fixed Initial Layer Status
- Got rid of the import lag due to Maxon's changes with script behavior
- Syntax Fixes to make variable names not match any preserved word syntaxes

Object Binder Changes
- Changed the line indention on script which makes Object Binder always make the whole scene invisible while moving the Object Binder Root.

Mesh Set Updates:
- Merged Steve and Alex Mesh

---------
Build 0089

Bone Set Updates:
- Controller Visibility Fixed for Local and Global Hand controllers

Facial Rig Updates
- Fixed unusual artifacts on both facial rig
- Fixed Inheritance V2 UVW Map
- Fixed misread of User Data for Customizable Teeth

Facial Addons Updates
- Fixed position of Teeth Container (Reset to origin)
- Fixed default color display of Eyebrow Color to OFF

Mesh Set Updates:
- Added a script to change SSS Mode from Steve to Alex version prior to Mesh Merge

----------
Build 0090

Mesh Set Updates:
- Fixed Mesh Mismatch for High-Poly Tier
- Fixed Mesh Lock error on Extrusion Assistant
- Fixed Extrusion Assistant Visibility Error for Alex Arms (Prior to Mesh Merge)

----------
Build 0090 HotPatch (November 08, 2020)

Mesh Set Updates:
- Fixed FreesizeMesh Head UV Map

----------
Build 0091

Importer Updates
- Added Cape Texture Field
- Added CodeGen Core (Useful for copy-pasting Importer Settings, including Character Name. Can be used for bug reporting)

Mesh Set Updates:
- Fixed SSS Independency on Main Package

----------
Build 0091 LayerFix (November 29, 2020)

Facial Rig Updates:
- Removed 2 faulty nodes

----------
Build 0091 UserDataFix (December 05, 2020)

Importer Updates:
- Added another User Data that lets you choose which to have as an Active Object after Importer Run

Qube Set Updates:
- Updated Pupil Object Reference in accordance to Facial MoCap Expansion Pack (Co-Developed with FrostTheNetwork)

----------
Build 0092

Pack Updates:
- Removed version indicator on the preset folder name itself.
- Uses a new version indicator (You can check your version via the UCR Help Block now)

Importer Updates:
- Minor Code Rewrite

Facial Rig Updates:
- Minor XPresso Rebuild
- Added a Separate Mode Eyelid Multiplier Control on the Q-Adapter
- Added a switch that hides the Q-Adapter
- Tweak for Compatibility: Facial Animator Pack (LipSync, AutoBlink and Face MoCap)

UCR Help Block Updates:
- Version field added.

----------
Build 0092 Express Patch (December 11, 2020)

Facial Rig Updates:
- Compatibility fixes for LipSync Override
- Added another control (for the Lipsync Override Mode)
- Fixed Control Switch Lag

----------
Build 0093

ObjectBinder Updates:
- Added a Cape Field and Shortcut Key

UCR Help Block Updates:
- Changed VersionChecker Target Address prior to the website transfer.

Mesh Updates:
- Fixed unlinked deformations for Alex Arms
- Added new deformers

Bones Updates:
- Updated the reset commands section from manual input to press-and-run system
