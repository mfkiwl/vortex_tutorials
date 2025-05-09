# Vortex Workshop and Tutorials at [MICRO-57 (3rd November 2024)](https://microarch.org/micro57/index.php)

Description:

[Vortex](http://vortex.cc.gatech.edu/) is an [open-source](https://github.com/vortexgpgpu/) hardware and software project to support GPGPU based on RISC-V ISA extensions. Currently, Vortex supports OpenCL/CUDA and it runs on FPGA. The Vortex platform is highly customizable and scalable with a complete open-source compiler, driver and runtime software stack to enable research in GPU architectures. This event includes both a workshop and tutorial. The tutorial will cover Vortex's hardware, software, applications, and provide hands-on exercises. The workshop brings together Vortex developers and researchers to discuss and present their Vortex-related research.

## Date: 2024-11-3 (8:00AM - 12:00PM CST)

## Organizers:

Hyesoon Kim (Georgia Institute of Technology)

Blaise Tine (University of California, Los Angeles)

Jeff Young (Georgia Institute of Technology)

Aaron Jezghani (Georgia Institute of Technology)

Jaewon Lee (Georgia Institute of Technology)

Seonjin Na (Georgia Institute of Technology)

Liam Cooper (Georgia Institute of Technology)

Chihyo (Mark) Ahn (Georgia Institute of Technology)

## Tentative Tutorial Schedule

| Time        | Contents                                    | Presenter         | slides |
|-------------|---------------------------------------------|-------------------|--------|
| 8:00-8:20   | Intro and GPU background                    | Hyesoon Kim       | [slides](./Slides_MICRO56/1.tutorial_introduction_background.pptx)       |
| 8:20-9:20   | Vortex Microarchitecture and Software Stack | Blaise Tine       | [slides1](./Slides_MICRO56/2.vortex_microarchitecture.pptx) [slides2](./Slides_MICRO56/3.vortex_software_stack.pptx)       |
| 9:20-9:40   | CuPBoP: Running OpenCL and CUDA on Vortex   | Chihyo (Mark) Ahn | [slides](./Slides_MICRO56/cupbop.pptx)      |
| 9:40-10:00  | Q&A Session                                 |                   |        |
| 10:00-10:20 | Coffee Break                                |                   |        |
| 10:20-11:00 | FPGA Demo & Hands-on Assignments            | Liam Cooper       | [slides](./Slides_MICRO56/fpga_and_assignments.pptx)      |
| 11:00-12:00 | Vortex Workshop (3 Speakers)                |                   |        |

## Tutorial Assignments

Provided are seven hands-on tutorial assignments covering various aspects of Vortex:

[Assignment 1](Exercises/assignment1.md) and [Assignment 2](Exercises/assignment2.md) add a warp efficiency performance counter in Vortex's cycle-level simulator and RTL respectively.

[Assignment 3](Exercises/assignment3.md) and [Assignment 4](Exercises/assignment4.md) add software prefetching to the cycle-level simulator and RTL respectively.

[Assignment 5](Exercises/assignment5.md) and [Assignment 6](Exercises/assignment6.md) add a new custom RISC-V instruction for computing the integer dot product in the cycle-level simulator and RTL respectively.

[Assignment 7](Exercises/assignment7.md) teaches how to debug Vortex.

## Getting Vortex

### Remote Access
A terminal interface hosted by the [CRNCH Rogues Gallery](https://crnch-rg.cc.gatech.edu/) is provided. [Instructions can be found here](./REMOTE_ACCESS.md).

### Docker (Experimental)
See the [Docker instructions](./docker/README.md) for how to set up a Docker image for Vortex.


### System Set Up Instructions
If you would like to set up Vortex on your own system, [instructions can be found here](https://github.com/vortexgpgpu/vortex/blob/master/docs/install_vortex.md).

## Relevant Repos

* [Vortex](https://github.com/vortexgpgpu/vortex)
* [Vortex Toolchain](https://github.com/vortexgpgpu/vortex-toolchain-prebuilt)

## Mailing list
For tutorial info please join vortex-dev@lists.gatech.edu 

