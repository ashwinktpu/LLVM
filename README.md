
### Note ::
```
The PTX or CUBIN file runs on GPU and not on CPU.
When we load PTX via CUDA driver API (cuModuleLoadDataEx()) the GPU driver JIT compiler compiles it into SASS (native GPU machine code) for the current GPU Architecture.
CUBIN is a precompiled binary containing SASS. It avoids JIT compilation.

```


```
While installing NVIDA-toolkit it used to take the same path as nvidia-smi.
which nvidia-smi
/usr/bin
nvcc --version
......
It get replaced by the installation of the nvidia toolkit and can show blank.
So we can put the NVCC in a different path and keep nvidia-smi in /usr/bin



```
