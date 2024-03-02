# Gradients_on_the_Clock


## Phase 0: Design the prototype

### Setup computation: Setup the microcontroller and FPGA setup with your PC and try to perform a gradient descent computation. Develop and find the most efficient software and hardware pipeline (Checkpoint) which supports automatic differentiation.

### Design a basic Gradient Box: Design a 3D structure which can harbour the microcontroller, display, input-output lines, FPGA board and then print/make it. Inventory to be decided upon. What is the challenge? It must be very power efficient. Very.

### Perform a initial capcity study: Matrix Multiplication, Inversion and setting up the AutoDiff pipeline in C program over 4 target functions: Rasterin. Rosenbrock. Spherical. 

## Phase 1: Feasibility Study and Initial Prototype

#### Conceptualization: Start with a detailed feasibility study to explore the practical benefits and challenges of performing gradient computations from CUDA cores to specialized hardware like FPGAs in terms of power efficiency and computation speed.

#### Prototype with FPGA: Develop a prototype using an FPGA to emulate the ASIC's functionality. This step allows for experimentation with different algorithms and architectures without the high cost and inflexibility of ASIC fabrication. The FPGA can be used to perform gradient computations or other deep learning tasks, interfaced with a microcontroller or directly with a computer.

#### Software Interface: Create a basic software interface, possibly a Python module, that allows simple models in PyTorch to offload certain computations to the FPGA. This step involves understanding PyTorch’s extensibility to integrate external hardware accelerators.

## Scientific Goals of this Project:

### Precision/Accuracy: Determine the numerical precision needed for your computations. This affects the FPGA design, especially the choice between fixed-point and floating-point arithmetic.
### Power Consumption: Identify your power budget. This could influence the choice of FPGA and microcontroller, as well as the design of your algorithms to be power efficient.
### Wall Clock Time: Establish performance goals. Knowing your target speeds can help in designing the system architecture and parallelization strategy.
### Scalability: Plan for future expansion. Consider how the system might need to scale up in terms of complexity or processing power.
