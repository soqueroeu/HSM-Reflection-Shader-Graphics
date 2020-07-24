# HSM Reflection Shader Graphics

## 4K System graphics created specifically for use with the HSM Mega Bezel Reflection Shader.

This project is an attempt to provide end users with high quality art to use in conjunction with the amazing **Mega Bezel Reflection Shader** created by **HyperspaceMadness**.

While developing this art I have a few select goals.

* All art will be vector based.
* If raster effects are used at any point they will be 300dpi. This may include text layer imports from Photoshop.
* High quality is a must! When using existing art as a reference, it will be paired with photographic references in an effort to improve it's realism and give it a cohesive style.
* Final raster output of 4K at 300dpi
* All project files will be provided. Layer structure within the project files will assume that an end user may want to change the bezel size or placement, and *attempt* to make balancing the artwork easy.
* Inclusion of logo, night, plain, and 4K vertical versions, where they make sense.

Some screenshots...

![](/images/SNES.png)

![](/images/Gamecube.png)

![](/images/Super_Famicom.png)




Just in case you have never had the shader running, here is a quick guide to it and my graphics.

1.    First of all, I really recommend a fresh clean install of Retroarch, just to make sure nothing interferes. I couldn’t get the shader to work at all when I first tried, primarily because I was using an existing RA setup.

2.    Unpack the shader into the install and follow HSM’s instructions.

```
Set your video driver to Vulcan or GLCore

Set your video aspect ratio to your monitor aspect and set integer scale to OFF
```
    
3.    Install your core, load some content, and try one of the shader presets. (I have been designing around guest-dr-venom.

4.    Once it is working, make a small change in the parameters. (I usually change the “[BEZEL & FRAME COLOR] Color Value/Brightness - Def 10” from the default of 10 to 9.80. Save a shader core preset.

5.    Copy my graphics to a folder of your choice. I use “D:\Games\Retroarch\images”.

6.    Navigate to the shader preset you saved in step #4. e.g. “D:\Games\RetroArch\shaders\presets\Beetle PSX HW\Beetle PSX HW.slangp”, and open it in a text editor. At the end of the file modify this line,

![](/images/background_image_info.jpg)


to the path of my graphics. e.g. BackgroundImage = "../../../images/Playstation.png".

Make sure you are using one of my HSM shader graphics and not one of my RA overlays. (Although it would still work, you would have to fiddle with parameters to hide the bezel completely.)

Note: You can use an absolute path if you like but it will not be portable.

Save the file and give some content a spin. :grin:

