# gpu-burn
Multi-GPU CUDA stress test
- CUDAPATH=/usr/local/cuda-8.0/ # cuda的路径
- NVCC=/usr/local/cuda-8.0/bin/nvcc # nvcc的路径   如该不知道怎么找，请用whereis命令。
- make #会产生执行文件gpu_burn
以下二选一：
- ./gpu_burn 60    #60 是时间，单位是秒
- ./gpu_burn 60 |tee sreen2text.txt  # 把屏幕信息写入到sreen2text.txt文件中

