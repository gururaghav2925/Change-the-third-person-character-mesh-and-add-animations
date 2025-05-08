# Changing Third Person Character Mesh and Adding Animations in Unreal Engine

## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure

1. **Import New Character Mesh and Animations:**
   - In the **Content Browser**, import a new **Skeletal Mesh** along with its **Animations** (FBX files).
   - Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).

2. **Replace Character Mesh:**
   - Open the **ThirdPersonCharacter Blueprint** (usually found in `ThirdPersonBP/Blueprints`).
   - Select the **Mesh** component.
   - In the **Details Panel**, change the **Skeletal Mesh** to the newly imported mesh.

3. **Set Animation Blueprint:**
   - If available, assign a matching **Animation Blueprint** in the **Details Panel** under the **Animation** section.
   - If not available, create one:
     - Right-click in the Content Browser → **Animation → Animation Blueprint**.
     - Choose the correct skeleton.
     - In the AnimGraph, set up state machines or direct animation nodes.
     - Compile and save.

4. **Preview and Test:**
   - Place the character in the level.
   - Press **Play** to test idle, walk, and run animations based on character movement.
  
## Output

![Screenshot 2025-05-08 143434](https://github.com/user-attachments/assets/da92e5cf-9199-4e45-90e3-697916a28716)


![Screenshot 2025-05-08 143447](https://github.com/user-attachments/assets/98c10596-d453-4b40-b1c9-6fd5630b63ac)


![image](https://github.com/user-attachments/assets/b8b2a3ec-eab5-44a2-9213-097a6d7f7845)








## Result
The default Third Person Character was successfully replaced with a custom skeletal mesh, and animations were applied using an Animation Blueprint. The character now visually reflects new assets and performs the desired movement animations.
