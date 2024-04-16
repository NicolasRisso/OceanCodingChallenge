# OceanCodingChallenge
This is Nicolas Risso's submission for the Advancement Design coding challenge.

Implementations:

- Water simulated with Gerstner and Circular Waves.
- Waves generated using Gradient Noise.
- Water exhibits post-process effects when submerged, including a visible waterline when not completely underwater.
- Buoyancy system that allows objects to float on the water. This system uses pontoons to apply force to the object and works with Gerstner waves. (Note: The buoyancy system does not include friction, which means that the objects continue moving indefinitely.)
- Controllable boat that utilizes the buoyancy system (Simple Vehicle System).
- Infinite Ocean.

Difficulties:

- The waterline experiences glitches and does not align perfectly with the wave noise, resulting in minor imperfections. This issue is likely caused by the scaling of the ocean.
- Due to my limited knowledge of C++ and BP (Blueprint) integration, coupled with illness during the development phase, I focused solely on using BP. Despite this, I understand the importance of C++ for the company and am currently studying it to learn better implementation methods in UE5 (Unreal Engine 5).

Credits:
- Water Texture: https://3dtextures.me/2017/12/28/water-001/
