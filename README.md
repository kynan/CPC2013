# Performance-Portable Finite-element Computations from High-level Specifications with FFC and PyOP2

### **Florian Rathgeber**<sup>1</sup>, Graham Markall<sup>1</sup>, Lawrence Mitchell<sup>3</sup>, Nicolas Loriant<sup>1</sup>, David Ham<sup>1,2</sup>, Paul Kelly<sup>1</sup>

#### <sup>1</sup> Department of Computing, Imperial College London
#### <sup>2</sup> Grantham Institute for Climate Change, Imperial College London
#### <sup>3</sup> EPCC, University of Edinburgh

[Slides][1] from my [talk][2] at [CPC 2013][3], June 3-5, Lyon, France.

Contact: Florian Rathgeber, [@frathgeber](https://twitter.com/frathgeber)

## Abstract

We present a tool chain for the fully automated synthesis of
performance-portable finite-element solvers for multicore and GPGPU platforms
from high-level specifications. Our runtime code generation and just-in-time
compilation pathway takes finite-element forms in the domain-specific language
UFL to low-level code. Automatically generated finite-element assembly kernels
are passed to PyOP2, a domain-specific language for mesh-based simulation
codes, which acts as an intermediate abstraction layer for executing the
numerical kernels in parallel over an unstructured mesh. Easy integration of
our tool chain allows transparently adding performance portability to existing
simulation codes.

## Resources

All the code is open source under BSD or LGPLv3 license

### PyOP2
<https://github.com/OP2/PyOP2>

### FFC
<https://bitbucket.org/mapdes/ffc>

### Firedrake
<https://code.launchpad.net/~fluidity-core/fluidity/firedrake>

### Benchmarks
<https://github.com/OP2/PyOP2_benchmarks>

### This talk
<http://kynan.github.io/CPC2013>

[1]: http://kynan.github.io/CPC2013
[2]: http://labexcompilation.ens-lyon.fr/cpc2013/program/
[3]: http://labexcompilation.ens-lyon.fr/cpc2013/
