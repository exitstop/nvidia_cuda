# nvidia cuda
------------------------------
Lubuntu 17.04 
------------------------------
    sudo apt-get install nvidia-cuda-dev nvidia-cuda-toolkit nvidia-nsight
    nvcc -ccbin clang-3.8 add.cu -o add #<-----compilation
    sudo nvprof ./add
