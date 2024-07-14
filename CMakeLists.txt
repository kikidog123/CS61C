cmake_minimum_required(VERSION 3.27)
project(61c C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(sp24-lab-starter/lab02)
include_directories(sp24-lab-starter/lab07)
include_directories(sp24-proj1-starter/src)
include_directories(sp24-proj4-starter/src)

add_executable(61c
        sp24-lab-starter/lab01/ex1_hello.c
        sp24-lab-starter/lab01/ex2_pointer_basics.c
        sp24-lab-starter/lab01/ex3_pointers_and_functions.c
        sp24-lab-starter/lab01/ex4_arrays.c
        sp24-lab-starter/lab01/ex4_arrays_updated.c
        sp24-lab-starter/lab01/ex5_pointer_arithmetic.c
        sp24-lab-starter/lab01/ex5_pointer_arithmetic_updated.c
        sp24-lab-starter/lab01/ex6_strings.c
        sp24-lab-starter/lab01/ex7_strcpy.c
        sp24-lab-starter/lab01/ex7_strcpy_fixed.c
        sp24-lab-starter/lab01/ex8_structs.c
        sp24-lab-starter/lab02/bork.c
        sp24-lab-starter/lab02/ex1_ptr_heap_stack.c
        sp24-lab-starter/lab02/ex2_compiler_warnings.c
        sp24-lab-starter/lab02/ex6_valgrind.c
        sp24-lab-starter/lab02/ex7_test_vector.c
        sp24-lab-starter/lab02/ex7_vector.c
        sp24-lab-starter/lab02/ex7_vector.h
        sp24-lab-starter/lab02/ex8_double_pointers.c
        sp24-lab-starter/lab02/ex9_cycle.c
        sp24-lab-starter/lab02/ex9_cycle.h
        sp24-lab-starter/lab02/ex9_test_cycle.c
        sp24-lab-starter/lab02/pwd_checker.c
        sp24-lab-starter/lab02/pwd_checker.h
        sp24-lab-starter/lab02/test_pwd_checker.c
        sp24-lab-starter/lab07/ex1.c
        sp24-lab-starter/lab07/ex1.h
        sp24-lab-starter/lab07/ex1_test.c
        sp24-lab-starter/lab07/ex2.c
        sp24-lab-starter/lab07/ex2.h
        sp24-lab-starter/lab07/ex2_test.c
        sp24-lab-starter/lab07/openmp_example.c
        sp24-proj1-starter/src/asserts.c
        sp24-proj1-starter/src/asserts.h
        sp24-proj1-starter/src/custom_tests.c
        sp24-proj1-starter/src/interactive_snake.c
        sp24-proj1-starter/src/snake.c
        sp24-proj1-starter/src/snake_utils.c
        sp24-proj1-starter/src/snake_utils.h
        sp24-proj1-starter/src/state.c
        sp24-proj1-starter/src/state.h
        sp24-proj1-starter/src/unit_tests.c
        sp24-proj4-starter/src/compute.h
        sp24-proj4-starter/src/compute_naive.c
        sp24-proj4-starter/src/compute_optimized.c
        sp24-proj4-starter/src/compute_optimized_mpi.c
        sp24-proj4-starter/src/coordinator.h
        sp24-proj4-starter/src/coordinator_mpi.c
        sp24-proj4-starter/src/coordinator_naive.c
        sp24-proj4-starter/src/io.h)
