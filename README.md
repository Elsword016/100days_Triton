# Project Progress

| **Day** | **Summary**|
|-----|--------------------------|
|Day1  | `1d_addition.ipynb` : Simple 1D vector addition kernel; breaking down the triton syntaxes and understanding it. Benchmarking against pure `torch` using the in-built tools |
|Day2  | `matrix_add.ipynb` : Kernel to add two 2d matrices; learn how to write 2d grids, offsets. Benchmarking against pure `torch` using `triton.testing.Benchmark` |
|Day3  | `matrix_multi.ipynb` : Kernel to do matrix multiplication and benchmark again pure `torch.matmul` |
|Day4  | `greyscale.ipynb` : Kernel to convert a 2d RGB (H,W,3) image to greyscale and then benchmarked it with a simple Pytorch implementation. Benchmarked using `triton.testing.Benchmark`|
