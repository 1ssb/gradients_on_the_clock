# Gradients_on_the_Clock


## Phase 0: Fround preparation --> Design the prototype

### Setup computation: Setup the microcontroller and FPGA setup with your PC and try to perform a gradient descent computation. Develop and find the most efficient software and hardware pipeline (Checkpoint) which supports automatic differentiation.

### Design a basic Gradient Box: Design a 3D structure which can harbour the microcontroller, display, input-output lines, FPGA board and then print/make it. Inventory to be decided upon. What is the challenge? It must be very power efficient. Very.

### Perform a initial capcity study: Matrix Multiplication, Inversion and setting up the AutoDiff pipeline in C program over target optimization functions.

#####################################################################################################################################################################################

## Scientific Goals of this Project:

### Precision/Accuracy: Determine the numerical precision needed for your computations. This affects the FPGA design, especially the choice between fixed-point and floating-point arithmetic.
### Power Consumption: Identify your power budget. This could influence the choice of FPGA and microcontroller, as well as the design of your algorithms to be power efficient.
### Wall Clock Time: Establish performance goals. Knowing your target speeds can help in designing the system architecture and parallelization strategy.
### Scalability: Plan for future expansion. Consider how the system might need to scale up in terms of complexity or processing power.
