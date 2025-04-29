
### Note ::
```
The PTX or CUBIN file runs on GPU and not on CPU.
When we load PTX via CUDA driver API (cuModuleLoadDataEx()) the GPU driver JIT compiler compiles it into SASS (native GPU machine code) for the current GPU Architecture.
CUBIN is a precompiled binary containing SASS. It avoids JIT compilation.

```
