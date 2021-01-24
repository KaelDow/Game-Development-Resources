# Game-Development-Resources

## Software
### Unity
https://docs.unity3d.com/Manual/UnityManual.html

### Blender
https://www.youtube.com/watch?v=1jHUY3qoBu8 Learn Low Poly Modeling
https://www.youtube.com/watch?v=dclA9iwZB_s How Great First-Person Animations are Made - 10 Tips for Animating FPS Characters/Weapons in Blender

### paint.net


## Unity Tutorials
### Input
[New Unity Input System (youtube)](https://youtu.be/zIhtPSX8hqA)

Do not drag the controls class into the attached script, instead do this
```
    private Controls _controls;

    void Awake()
    {
        _controls = new Controls();
    }
```


https://www.youtube.com/watch?v=Pzd8NhcRzVo

[Converting your game to DOTS - Unite Copenhagen](https://www.youtube.com/watch?v=BNMrevfB6Q0)

### UI
[Use UI in multiple scenes (youtube)](https://www.youtube.com/watch?v=6ztY9-IX3Qg)
* Covers additive scene loading which could be useful for other things, e.g. a Boarderlands style inventory screen, or showing a vehicle or building interior 

### Movement
[FIRST PERSON MOVEMENT in Unity - FPS Controller](https://www.youtube.com/watch?v=_QajrabyTJc&t=70s)

### Camera
https://unity.com/unity/features/editor/art-and-design/cinemachine

### Level creation

unity pro builder

### Mesh Combiner

### DOTS
https://unity.com/dots - scroll to near the bottom for tutorial
Data-Orientated Technology Stack is a combination of ECS, the Job System and the Burst Compiler
https://www.youtube.com/watch?v=BNMrevfB6Q0

### Animating a Character
https://unity3d.com/how-to/turn-character-into-player

### Editor Scripts
https://www.youtube.com/watch?v=WP-Bm65Q-1Y&list=PLFt_AvWsXl0eBW2EiBtl_sxmDtSgZBxB3&index=2

## Blender Tutorials

[Rigging](https://www.youtube.com/watch?v=srpOeu9UUBU)

## Assets
### 3D models
http://devassets.com/ (pay what you want)

[Synty Studios Unity Assetstore (low poly, paid)](https://assetstore.unity.com/publishers/5217)

### Music
https://www.freemusicarchive.org/search

## Procedural Generation

## Grids

### Hex Grids
https://www.redblobgames.com/grids/hexagons/

### Protips
* Combine meshes when possible to reduce the number of render calls made each frame
* For an FPS use two cameras, one for everything the player can see of themselves/their equipment and a second that allows the player to change their FOV without making the stuff in the first camera look wonky
