# Unity Project Template

Folder structure as of 16/03/2022.  
This is updated with 2020.3.30f1 LTS, but the folder structure will work on all versions.  

All folders include a small .gitkeep file in case GitHub wants to delete empty folders, all of these can be deleted whenever, but I recommend that you have a .gitkeep file in all your empty folders here on GitHub in the future.  
Enjoy!

# Unity — Project and Scene Structure

Having an organized project structure as well as scene hierarchy is beneficial to your project and your team.  

### Project

* Test 1   

### Scene

- All empty objects should be located at 0,0,0 with default rotation and scale.
- When you’re instantiating an object in runtime, make sure to put it in _Dynamic – do not pollute the root of your hierarchy or you will find it difficult to navigate through it.
- For empty objects that are only containers for scripts, use “@” as prefix – e.g. @ScriptName.
- Try using prefabs for everything if possible, it will make the workflow feel a lot smoother - e.g. you don't need to make a new player for each stage, just add the prefab for the player that you've saved already.

# Created By

- Stig Omdal

# Contact

- Twitter - <a href="https://twitter.com/stigping/">@stigping</a>
- Git - <a href="https://github.com/StigPing/">Github.com/StigPing</a>
- LinkedIn - <a href="https://Linkedin.com/in/stigping">Linkedin.com/in/stigping</a>