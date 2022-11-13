### David Neto

* I'm on the Chrome team at Google.
* I work on GPU language standards, compilers, and related tooling.
* I am an editor of the W3C's <a href="https://w3.org/TR/WGSL">WebGPU Shading Language (WGSL) specification</a>
* I have contributed to <a href="https://www.khronosgroup.org">Khronos Group</a> standards, particularly:
    * <a href="https://www.khronos.org/spir/#:~:text=SPIR%201.2/2.0%20Resources">SPIR</a> the original LLVM-based one, when I still worked at Altera.
    * <a href="https://www.khronos.org/spir/#:~:text=SPIR%2DV%20Language%20Ecosystem">SPIR-V</a>, the one used by Vulkan and more recent OpenCL versions.
    * <a href="https://www.vulkan.org/">Vulkan</a>, mainly shader-related things, and the Vulkan Memory Model
* I have contributed to:
    * [SPIRV-Tools](https://github.com/KhronosGroup/SPIRV-Tools): low level SPIR-V utilities: assembler, disassemler, parser, validator, optimizer
    * [Clspv](https://github.com/google/clspv): Prototype OpenCL C to Vulkan SPIR-V compiler
    * [DXC](https://github.com/microsoft/DirectXShaderCompiler)'s Vulkan SPIR-V backend
           <details><summary>Team lead and mentor</summary>I said we should do it, could do it, staffed it, and said it should completely avoid using LLVM IR.
               Also, I wrote the effcee testing harness so we could write FileCheck-like tests that ran very fast in googletest.</details>
    * [Amber](https://github.com/google/amber): A text-based shader test framework
    * [Effcee](https://github.com/google/effcee): A library clone of LLVM's FileCheck, basically. For fast in-process testing such as in googletest.
    * [Tint](https://dawn.googlesource.com/tint): A compiler for WGSL.  (My contribution is particiularly the SPIR-V to WGSL conversion.)
* Find me at <a href="https://mastodon.gamedev.place/web/@dneto" rel="me">@dneto@mastodon.gamedev.place</a>
