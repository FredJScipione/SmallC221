# SmallC221
The github repository is currently under construction.

Small-C 2.2.1 is my attempt to help keep the Small-C compiler available and viable.

Since its first appearance in the May 1980 issue of "Dr. Dobb's Journal of Computer Calisthenics & Orthodontia",
Small-C retains 3 appeals -

1. As a teaching tool that provides a full working example with FOSS source code.

2. As a historical artifact from the early development of personal computers.

3. As a baseline small project that can be adapted by a small team (or an individual)
for new or otherwise un-supported CPUs (e.g. a custom FPGA cpu design).

I look at Small-C like a restored Model-T car.  It will probably never be a world-beater,
but it is more interesting if it can actually run :-).

The project includes not only the (updated) compiler, but also full tool chains,
from editor to OS & host machine emulator(s).

Source code updates include corrections, extensive comments, support for cross-compiling,
and enhancements.  All sources can be compiled via Small-C, K&R-C, or ISO-C.

Notably, the compiler now (also) targets IA32 processors (Win32 & Linux-x86) with
Right-to-Left argument evaluation (& stacking) possible for greater target OS compatibility.
