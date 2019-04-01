SNES-SPC700 Sound File Loader for IDA
=====================================

This is a IDA processor plugin module for SNES SPC700.

With [SPC700 loader plugin](https://github.com/gocha/ida-snes_spc-ldr), you can load a SPC file into IDA 6.x.

**IMPORTANT NOTICE**:
This plugin is not compatible with IDA 7.0 or later. In IDA 7.0, Hey-Rays has made breaking changes on IDA API design and has been released an [migrating guide](https://www.hex-rays.com/products/ida/7.0/docs/api70_porting_guide.shtml). I don't plan to maintain this project to follow new IDA API design at the moment. I think I will try to make an IDAPython plugin from scratch instead, when I seriously need an extension for SNES reverse engineering, but I really don't need that very soon.

How to compile
--------------

1. Download and install [IDA SDK](https://www.hex-rays.com/products/ida/support/download.shtml) (expected version is IDA SDK 6.9)
2. Clone the repository into $(IDASDK)/module/spc700
3. Compile the project with [Visual Studio](https://www.visualstudio.com/downloads/download-visual-studio-vs.aspx)

Read official development guides for more details of generic IDA development.
