### Shazzam 
> Shazzam is the editor and compiler of HLSL shader， it can compile fx file to ps file（which is available for WPF）. For more detail you can see WPF 像素着色器入门：使用 Shazzam Shader Editor 编写 HLSL 像素着色器代码 - walterlv
https://blog.walterlv.com/post/create-wpf-pixel-shader-effects-using-shazzam-shader-editor.html

### Download
> Link: Shazzam Shader Editor - CodePlex Archive
https://archive.codeplex.com/?p=shazzam

### Issues you may achieved
In some computer the editor will give you the **"can not find csc.exe" tips.** The reason is missing *.NET 3.5*. Install .NET 3.5 can fix this problem.

### HLSL
HLSL is the High Level Shading Language for DirectX. Using HLSL, you can create C like programmable shaders for the Direct3D pipeline.

HLSL was created, starting with DirectX 9, to set up the programmable 3D pipeline. You can program the entire pipeline with HLSL instructions.

You can set WPF PS_3 to support complicate shader, but be careful of you calculation, focus on you GPU algorithm.
