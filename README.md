# EnhancedPtrs: Advanced Smart Pointer Implementation in C++

This repository contains a custom implementation of smart pointers in C++. Smart pointers are a powerful feature of the C++ language that help manage the lifetime of dynamically allocated objects and prevent memory leaks.

## Introduction

Smart pointers in C++ provide automatic memory management for dynamically allocated objects. They are designed to handle the ownership and lifetime of resources, ensuring that memory is properly allocated and deallocated without manual intervention.

In this project, we aim to implement custom smart pointers that mimic the behavior of C++ standard smart pointers such as `std::unique_ptr` and `std::shared_ptr`. By doing so, we will gain a deeper understanding of the underlying mechanisms and concepts involved in smart pointer management.

## Features

- Implementation of custom `SharedPtr` and `UniquePtr` classes
- Memory management through ownership transfer and reference counting
- Basic memory leak prevention
- Utilization of C++ features like operator overloading and templates

## Getting Started

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/[your-username]/custom-smart-pointers.git
   ```
2. Run the cmake command from the build directory:

   ```bash
   mkdir build
   cd build
   cmake ..
   ```







