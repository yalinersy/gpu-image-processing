# GPU Image Processing
# Description
This project demonstrates GPU-accelerated image processing using Python and OpenCV in a Kaggle Notebook. An image inversion filter was applied using both CPU and GPU to compare performance.

# Tools Used

Python

OpenCV

Numba CUDA

Kaggle Notebook (GPU Accelerator)

# GPU Usage

GPU was enabled in Kaggle Notebook settings under Accelerator → GPU.
The CUDA kernel processed image pixels in parallel, resulting in faster execution time compared to CPU.

# How to Run

Open the notebook in Kaggle

Turn Accelerator = GPU in right panel

Run all cells

Output image will be saved in /kaggle/working

# Output

# CPU Time vs GPU Time comparison


<img width="1919" height="1094" alt="Cpu" src="https://github.com/user-attachments/assets/6281a2e2-b0e9-4654-ab64-20cf5b5d2573" />
<img width="1919" height="1085" alt="Gpu" src="https://github.com/user-attachments/assets/5ca7d90e-75ee-435e-840c-9d98659a13b4" />


# Filtered output image


<img width="558" height="369" alt="image" src="https://github.com/user-attachments/assets/d459f84a-45b5-415a-8de4-5af278360192" />

