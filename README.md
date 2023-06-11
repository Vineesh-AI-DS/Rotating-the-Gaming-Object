# Ex-1 Rotating-the-Gaming-Object

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
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

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
```
Program created by: Vineesh.M
Register number: 212221230122
```
## Rotate along x-axis:

```cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class updown : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {

    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.up, Vector3.right, 90 * Time.deltaTime);
    }
}
```
## Rotate along y-axis:
```cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class name : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {

    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.right, Vector3.down, 90*Time.deltaTime);
    }
}
```

## Output:

![arvrop](https://user-images.githubusercontent.com/93427254/226115833-a9532ca8-055e-4d5f-a80d-c431103bdec6.png)
![vrop](https://user-images.githubusercontent.com/93427254/226115835-f523d318-6e8d-4ee3-92b5-5075c125651b.png)

## Result:
Thus a 3D application for rotating the gaming objects in unity is developed successfully.
