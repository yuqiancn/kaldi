Trying to build kaldi in gentoo linux, now failed.
试图在gentoo系统上安装kaldi，失败了，kaldi/src/下配置命令为：

```
./configure --mkl-root=/usr/include/mkl --mkl-libdir=/usr/lib64 --cudatk-dir=/opt/cuda --cuda-arch=sm_52
```

and there are some errors in compiling openfst.
