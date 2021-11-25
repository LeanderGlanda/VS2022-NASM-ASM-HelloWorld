# x86_64 assembler 'Hello World' with nasm in Visual Studio
Credits to ShiftMediaProject for creating the [NASM integration for Visual Studio](https://github.com/ShiftMediaProject/VSNASM).
The `nasm.props`, `nasm.targets` and `nasm.xml` file is from their repository.
You need to place them to `C:\Program Files\Microsoft Visual Studio\2022\Preview\Msbuild\Microsoft\VC\v170\BuildCustomizations` (In VS2022 Preview).

I added `NASMPATH` with the value `C:\Users\Leander\AppData\Local\bin\NASM\` to my environment variables and installed the latest version of NASM.