# Godot_Workshop_Febuary_2026
# 🚀 Godot 4 Workshop: Build Your First Level

## 1. Getting Started

- Download: Go to [godotengine.org](https://godotengine.org/). Download the "Godot Engine" (Standard version).
    
- Launch: Open the .exe. No installation is required!
    
- New Project: Click + New Project. Name it, create a folder, and choose the Compatibility renderer (best for all hardware).
    

## 2. Setting the Stage (Assets & Maps)

- Import Assets: Drag your folder of images/sprites into the FileSystem dock (bottom left).
    
- The World Scene: 1. Click 2D Scene in the center. 
    ![[Pasted image 20260204094850.png]]

- Well Create a 2D Node. On the scene tab select **2D Scene Node**. 
	![[Pasted image 20260204095026.png]]
1. Right click the 2D scene node and give it a helpful name. 
   ![[Pasted image 20260204095826.png]]
- Save the scene (Ctrl + S).

-  In the Scene tab Select the **+** icon this should bring up a new menu 
	![[Pasted image 20260204100848.png]]
- in the search bar type in TileMapLayer. and then click on the create button
    ![[Pasted image 20260204101639.png]]
-  In the Inspector (right side), lets create a new TileSet.
    ![[Pasted image 20260204101907.png]]
- Drag your ground sprites into the TileSet panel at the bottom.
    
- Paint: Use the "Paint" tool to draw your floor and platforms.
    

## 3. Creating the Hero

1. New Scene: Click the + tab at the top. Choose Other Node and search for CharacterBody2D.
    
2. Add Components: Right-click your CharacterBody2D and add:
    

- Sprite2D (To see the character).
    
- CollisionShape2D (To touch the ground).
    

4. Setup:
    

- Drag your character image into the Sprite's Texture slot.
    
- Click the CollisionShape, and in the Inspector, set the Shape to a "New RectangleShape2D." Stretch it to fit the sprite.
    

6. Save: Save this scene as player.tscn.
    

## 4. Coding the Logic

1. Select the CharacterBody2D node.
    
2. Click the Attach Script icon (the little scroll with a green plus).
    
3. Template: Choose the "Character Body 2D Basic Movement" template. This gives you gravity, jumping, and walking automatically!
    

## 5. Connecting Everything

1. Go back to your World scene.
    
2. Drag player.tscn from the FileSystem onto your map.
    
3. Play: Press F5. Select the world.tscn as the main scene. Use arrow keys to move and Space to jump!
