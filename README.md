# Large-Hash-CUDA-Collider
GTA 5 Natives collider CUDA Accelerated



COMPILE PROJECT AND EXECUTE

You should have installed CUDA ( Work only on Windows )

Use NVCC Compiler :
Open a command prompt and go to your directory and execute the command :
nvcc -run -arch=sm_30 -m=64 coll.cu

Use the good arch for your GPU, you can found documentation to compile with NVCC to :
http://docs.nvidia.com/cuda/cuda-compiler-driver-nvcc/#axzz4hoIl0y7H

When the program is launched, the file "NativesGPU.txt" is created in your desktop, the collisions is append to this file.


Bench on GTX 760 : ~3.5 Millions Hashs per second
Bench on GTX 1080 : ~11 Millions Hashs per second
