## Tutorial One

This tutorial will cover the creation of a basic main menu. To begin, create a new canvas in the hierarchy. It can be found under UI. Under the canvas create a panel. In the image component of the of the panel, which can be found in the inspector, set the source image to none and the colour to a dark tone with full opacity. This will form the simple background of the menu.

Create an empty game object under the canvas and rename it to "mainMenu" this will contain the menu buttons. Under the mainMenu object add three "Button - TextMeshPro" Within each button is a text object that can be edited to label each button. For this basic menu, label them as "Play", "Options" and "Exit".

Now, create a new C# script and call it "mainMenuScript" and add it to mainMenu. This will control all the buttons. First add the line "using UnityEngine.SceneManagement;" as shown below.
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;
```
This allows the script to load different scenes. Delete "void Update" and "void Start" as they are unnecessary for this script. Next we will create a function to start the game. To do this type "public void" then the name of the function followed by () {}. In this case I will use the name "PlayGame". Inside the function add the line "SceneManager.LoadScene(SceneManager.GetActiveScene().buildIndex + 1);" as shown below. This will load the second scene in your project's build settings.
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class mainMenuScript : MonoBehaviour
{
    public void PlayGame()
    {
        SceneManager.LoadScene(SceneManager.GetActiveScene().buildIndex + 1);
    }
}
```
