# GAME_PROGRAM-EX--1
# EX:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine
Name : Kurapati Vishnu Vardhan Reddy

Reg NO : 212223040103

# Aim:
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.


# Procedure:
1.Create a New Material: Open Unreal Engine. In the Content Browser, right-click and select Material. Name it M_EffectsDemo.

2.Apply Base Color: Open the material. Add a Vector Parameter or Constant3Vector node and connect it to the Base Color input. Add Emissive Effect:

3.Add a Multiply node. Connect a Constant3Vector (for emissive color) and a Scalar Parameter (for intensity). Connect the result to the Emissive Color input.

4.Control Roughness: Add a Scalar Parameter node and connect it to the Roughness input. Lower values = shinier surface, higher values = rougher surface.

5.Control Metallic Property: Add a Scalar Parameter node and connect it to the Metallic input. 0 = non-metal, 1 = fully metallic.

6.Save and Apply Material: Save the material. Apply it to any mesh in the scene (like a sphere or cube) to preview the results.

# Output:
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/3a051022-c853-42e5-9e39-c3e40cc2a895" />
<img width="1192" height="791" alt="image" src="https://github.com/user-attachments/assets/0d79833a-6a8a-4a2f-af48-2b3f335659ce" />

# Result:

Successfully implemented a material in Unreal Engine showcasing
Emissive glow using emissive color and intensity. Variable surface roughness to simulate different textures. Metallic appearance adjustment to reflect light like real-world metals. This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
