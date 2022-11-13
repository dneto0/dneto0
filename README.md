## About David Neto

* I work on GPU language standards, compilers, and related tooling.
* I'm on the Chrome team at Google since 2014.
* Between 2000 and 2014, I worked at Altera on FPGA architecture and CAD. From 2010-2014 I worked on OpenCL for Altera FPGAs.
* I am an editor of the W3C's <a href="https://w3.org/TR/WGSL">WebGPU Shading Language (WGSL) specification</a>
* I have contributed to <a href="https://www.khronosgroup.org">Khronos Group</a> standards, particularly:
    * <a href="https://www.khronos.org/opencl">OpenCL</a> (when I was at Altera)
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
* I've been a vim user since 1994.
* I completed a Computer Science PhD at the University of Toronto in 1999, under the supervision of Prof. Derek Corneil:
    *Efficient Cluster Compensation for Lin-Kernighan Heuristics*, [PDF](http://www.cs.toronto.edu/dcs/theses/PhD/1998-99/Neto.phd.pdf)
* I tend to overuse parenthesized sentences.
* Find me at:
    * GitHub: <a href="https://github.com/dneto0">@dneto</a> (My GitHub avatar is a fragment of a figure from my PhD thesis.)
    * Mastodon: <a href="https://mastodon.gamedev.place/@dneto" rel="me">mastodon.gamedev.place/@dneto</a>
