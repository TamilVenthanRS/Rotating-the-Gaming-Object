### EX NO:01 
### DATE: 
# <p align="center"> Rotating the Gaming Object</p>
## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step1:
Start
### Start2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Start3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Start4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
### Start5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Start6:
Create a folder name Coding and create a C# file to add the coding in it.

### Start7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Start8:
Stop

## Program:
```c#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class NewBehaviourScript : MonoBehaviour
{
    void Start()
    {
        
    }
    void Update()
    {
        transform.RotateAround(Vector3.right,Vector3.up,40*Time.deltaTime);
    }
}

```

## Output:
![2022-04-27 at 9 20 35 AM](https://user-images.githubusercontent.com/75235477/165436921-12f7b118-ab36-4a6b-a0dd-64d12a841392.jpeg)


## Result:
3D application for rotating the gaming objects in unity is devloped.
