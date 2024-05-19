cmake_minimum_required(VERSION 3.13)
project(gpu_fft C)
add_library(gpu_fft STATIC
    mailbox.c
    gpu_fft.c
    gpu_fft_base.c
    gpu_fft_twiddles.c
    gpu_fft_shaders.c
)