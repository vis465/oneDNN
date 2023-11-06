<div align="center">
<h1 align="center">
ONEDNN</h1>

</div>

## Project overview
**Medical Image Processing - Pneumonia classification**

   Pneumonia is a prevalent respiratory infection that requires accurate and timely
diagnosis for effective treatment. In our project, we utilized SYCL, a programming model based on standard C++,
for the classification of pneumonia in medical image processing. SYCL served as the foundation for our pneumonia classification project,
leveraging the power of heterogeneous hardware architectures, such as CPUs,
GPUs, and FPGAs.With SYCL, we optimized our classification algorithms for parallel processing, enabling faster and more accurate diagnosis

---

# 📍 What is OneAPI

   OneAPI is an open, standards-based, cross-architecture programming model developed by the oneAPI consortium, which is led by Intel. This initiative aims to simplify the development of high-performance, heterogeneous applications that can run on a variety of hardware architectures, including CPUs, GPUs, FPGAs, and other accelerators. It's designed to address the challenges of modern computing, where hardware diversity is increasing, and software needs to be optimized for different types of processors.

   <img src='https://www.intel.com/content/dam/developer/articles/technical/oneapi-what-is-it/f1-oneapi-specification-stack.png' />
<a href='https://www.intel.com/content/www/us/en/developer/tools/oneapi/toolkits.html'>Oneapi toolkit:link:</a>



---


# 📍oneDNN
oneAPI Deep Neural Network Library (oneDNN)
===========================================

<img align="left" src="https://spec.oneapi.io/oneapi-logo-white-scaled.jpg" alt="oneAPI logo">

oneAPI Deep Neural Network Library (oneDNN) is an open-source cross-platform
performance library of basic building blocks for deep learning applications.
oneDNN is part of oneAPI.
The library is optimized for Intel(R) Architecture Processors, Intel Graphics,
and Arm\* 64-bit Architecture (AArch64)-based processors. oneDNN has
experimental support for the following architectures: NVIDIA\* GPU,
AMD\* GPU, OpenPOWER\* Power ISA (PPC64), IBMz\* (s390x), and RISC-V.

oneDNN is intended for deep learning applications and framework
developers interested in improving application performance on CPUs and GPUs.
Deep learning practitioners should use one of the
applications enabled with oneDNN.



---
## Datasets:


1 Data sets are downloaded from kaggle 

2 Search for pneumonia using chest Xray and map the files into the code by aletring the path of training and test data

# ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                                                    | Summary                   |
| ---                                                                                                     | ---                       |
| [Pneumonia Prediction.cpp](https://github.com/vis465/oneDNN/blob/main/Pneumonia Prediction.cpp)         | HTTPStatus Exception: 401 |
| [Pneumonia Prediction.vcxproj](https://github.com/vis465/oneDNN/blob/main/Pneumonia Prediction.vcxproj) | HTTPStatus Exception: 401 |

</details>

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

• **Intel® oneAPI Base Toolkit** – it provides the environment for compiling for DPC++/ SYCL libraries

• **SYCL** – it provides process parallelism which makes the diagnosis efficient and effective

• **oneDNN** – Neural Network Classifier for pneumonia prediction

• **Opencv** - it is used for data preprocessing

### 🔧 Installation

1. Clone the oneDNN repository:
```sh
git clone https://github.com/vis465/oneDNN
```

2. Change to the project directory:
```sh
cd oneDNN
```

3. Install the dependencies:
```sh
g++ -o myapp 'Pneumonia Prediction.cpp'
```

### 🤖 Running oneDNN

```sh
./a
```

## Output and Analysis Workflow

**SYCL output with runtime**
<img src="https://drive.google.com/uc?id=1rAKjAyYELabCE_uXoL5uaSZJ1XhNmdVX" alt="Image Description">

**Analysis Workflow**
<img src="https://drive.google.com/uc?id=1ZB5CmaDnr5BBVdIsKnrmatfUQgxoJ6xx" alt="Image Description">



