<p align="center">
  <img width="468" alt="Screenshot" src="https://github.com/user-attachments/assets/1c05c111-f907-4f4a-9181-3b43ec69f0e4" />
</p>

This is an [ISF shader](https://isf.video) to plot a
[Lorenz system](https://en.wikipedia.org/wiki/Lorenz_system), converted from
[this ShaderToy shader](https://www.shadertoy.com/view/XddGWj).

This is a multi-pass shader that is intended to be used with floating-point
buffers. Not all ISF hosts support floating-point buffers.
[Videosync](https://videosync.showsync.com/download) supports floating-point
buffers in
[v2.0.12](https://support.showsync.com/release-notes/videosync/2.0#2012) and
later, but https://editor.isf.video does not appear to support floating-point
buffers. This shader will produce *very* different output if floating-point
buffers are not used.
