# Тест
add_executable(test_gpu test_gpu.cpp)
target_link_libraries(test_gpu PRIVATE fft_cuda signal_utils)
