# GAME_PROGRAM-EX--8
# Landscape Creation and Foliage in Unreal Engine

## Aim
To create a landscape in Unreal Engine, apply a custom landscape material, and add foliage for realistic environment generation.

## Procedure

1. **Create a New Landscape:**
   - Open your Unreal Engine project.
   - Go to the **Modes Panel** and select **Landscape**.
   - Set the desired section size, number of components, and overall resolution.
   - Click **Create** to generate the landscape.

2. **Apply a Landscape Material:**
   - In the **Content Browser**, create a new **Material** and name it `M_Landscape`.
   - Open the material and:
     - Use **Landscape Layer Blend** to blend textures (e.g., grass, rock, dirt).
     - Connect appropriate texture samplers to different layers.
     - Output the final blend to the **Base Color**, **Normal**, and optionally **Roughness** inputs.
   - Save the material.
   - Select the landscape in the scene, go to the **Details Panel**, and assign `M_Landscape` to the **Landscape Material** slot.

3. **Add Foliage:**
   - Go to the **Foliage Mode** from the **Select Mode dropdown**.
   - In the **Foliage Panel**, click the **+** icon to add Static Meshes (e.g., trees, grass, bushes).
   - Adjust settings like **Density**, **Scale**, and **Randomness**.
   - Use the brush tool to paint foliage onto the landscape.

## Output
<img width="1042" height="561" alt="Screenshot 2026-10-05 203851" src="https://github.com/user-attachments/assets/3dd71a92-8b73-4884-a300-8c708f61207b" />

<img width="1047" height="577" alt="Screenshot 2026-10-05 203859" src="https://github.com/user-attachments/assets/9886397e-89a5-4301-a4bb-2d108858aeb1" />


## Result
A landscape and Foliage in Unreal Engine was successfully created 

