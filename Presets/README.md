# HSM Reflection Shader Graphics Presets

These are graphic presets using mostly the GUEST-DrVENOM preset. (With the exceptions of GBA and PSP which use the LCD-GRID and the n64 which uses the GUEST-DrVENOM__N64)

Until the shader is final I am only doing presets for the "logo" versions of my graphics. I have changed a few default settings, such as, BGImage vignette is turned off, bezel noise is reduced to 10, and I have given most bezels a custom color.

These presets depend on the graphics being in the overlay directory and a bezel subdirectory keeping the repo folder structure. So... the complete path to the images is "\RetroArch\overlays\bezel\Logo".

Copy the presets into your shader folder. (\RetroArch\shaders)

Load your content and then a preset. I recommend creating a core preset next. If you plan on doing any manual tweaking to the *.slangp you need to make some small change in the shader parameters before you create a core preset. I usually nudge the "[BEZEL & FRAME] Color Value/Brightness" just a bit because such a small change is insignificant.

I will try to keep these updated as the shader is updated.
