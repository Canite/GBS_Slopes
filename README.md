# GBS_Slopes
A plugin for adding slopes functionality to GBStudio  
This plugin modifies engine/src/states/platform.c so will be incompatible with any plugins modifying the same file  
This plugin is only for 45 degree and 22.5 degree slopes and only for platformer mode  

https://github.com/Canite/GBS_Slopes/assets/7261074/0b5a187c-2d98-4eb2-9db8-8d9771b4923e

## How To Use
- Copy the plugins/ folder into your GBStudio project folder
- To set up the collisions for slopes, use these collision patterns
  - 45 degree right slope: Collision Right (5) + FIELD_COLLISION_LADDER (6)
  
  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/f398a9a7-6132-4756-833f-0eb71727c594)
  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/8e2c50f4-88f2-43ce-bb68-1b6bf965f462)

  - 45 degree left slope: Collision Left (4) + FIELD_COLLISION_LADDER (6)

  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/d6bec46d-3d91-47fc-8207-a149c27b9972)
  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/9564f736-06b3-4ef6-a08d-b4a3329b3e49)

  - 22.5 degree right slope bottom: Collision Right (5) + Collision Bottom (3) + FIELD_COLLISION_LADDER (6)  
    (Hold shift and left click to multi-select collision types)

  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/c58580a1-6208-40ae-b61d-0abfb4545577)
  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/3943b5af-c04d-4c0a-ad7a-551ce5ca94f9)

  - 22.5 degree right slope top: Collision Right (5) + Collision Top (2) + FIELD_COLLISION_LADDER (6)

  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/aabad801-68ac-4aba-a2a4-c137cb85ab3d)
  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/ab309d75-8a02-4550-83bd-efcbc51db558)

  - 22.5 degree left slope bottom: Collision Left (4) + Collision Bottom (3) + FIELD_COLLISION_LADDER (6)

  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/15fe5a17-82ae-440b-b5d2-a5dcf7135e2a)
  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/3565aa95-b068-4f38-9ba8-3499deb91d0d)

  - 22.5 degree left slope top: Collision Left (4) + Collision Top (2) + FIELD_COLLISION_LADDER (6)

  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/d3f4cf5e-deba-4677-a5e8-03345f2bbcb0)
  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/f8e5563c-7c87-44db-81f1-f97270bd3669)

  ![image](https://github.com/Canite/GBS_Slopes/assets/7261074/5d150bbc-a040-4b0f-8e22-9c726b47220b)
