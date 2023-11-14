
# How to mod Minecraft the easy way For Dummies 

Today I will teach you how to make your own mod in Minecraft versions (1.14.* {Fabric} & 1.16.5 {Forge}) and onwards.

This does not teach you how to install or play Minecraft, I'm pretty sure we all learned that at a early enough age.

## Inital Setup

### [IntelliJ IDEA](https://www.jetbrains.com/idea/)
First we are going to need our [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment) for making the mod IntelliJ Idea Community Edition. This is the main program for making mods for minecraft. 


---
>Head to the [downloads section](https://www.jetbrains.com/idea/download/?section=windows) on the Intellij website. Make sure to install the Community Edition as the Ultimate Edition is a 30 day free trial.


<details>
<summary></summary>

![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/cb2bc0a5-3029-4be5-8250-5eb49b6592bc)

Run the idealC-(yourversion).exe and make sure to accept the Admin Prompt.


<details>
<summary>Installer Settings</summary>

You can pick any location you prefer or just use the default location when it prompts you. 
 
![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/d4994c78-2fbb-428a-8bf6-68dc3a5f3373)

I personally use a custom location on my dev drive but this is not needed.
On the next page of the installer I highly recommend these options as the default is none.

![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/548e22d5-aef2-4f93-8f54-47b10723336e)

Then continue with the install as normal. Once it has finished it will prompt you to reboot.


</details>

Once you have installed IDEA, after the eula and anaylitics first-time options it will auto-detect if you have a Java jdk already installed, and prompt you to install one if you do not. If you have multiple jdk install versions it will let you pick your default for projects.

![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/cc6ddf5f-a7a5-4e3c-a918-b9f024b10b95)

Create a new empty project for now, as we need to make some changes to Idea before we can start modding Minecraft.

![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/d0cd05c8-234f-4e1a-a84f-7aeb6dacbfae)

 
<details>
 
<summary>Head to the settings </summary>

You do not need to update Kotlin unless you plan on using it, this tutorial will be java only


</details>

Go to the plugin tab, and make sure to install the Minecraft Development Plugin. You will need to restart IDEA for the plugin to take affect.

![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/8849fd44-e31a-4d8c-9877-581285598658)


<details>
<summary>My Plugins</summary>
 
![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/6207dc77-2949-4c92-8915-bae285de9aa2)


</details>

When you create a new project you should now see a option for Minecraft

![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/4ff55ed5-2e9a-4800-90bb-da979cbd7548)
![image](https://github.com/CantWeAllDisagree/MinecraftJunk/assets/110773497/b47a36b7-f560-44a8-a560-758eb168e4e6)




