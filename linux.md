#查看版本
```bash
nvcc --version
nvcc -V
```
nvcc -V有时候不一定有用


cudnn的版本：
8.0后使用新指令：
```bash
cat /usr/local/cuda/include/cudnn_version.h | grep CUDNN_MAJOR -A 2
```
