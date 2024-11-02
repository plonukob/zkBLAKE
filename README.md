# zkBLAKE

An attempt to implement the BLAKE2f hash algorithm as a zk-SNARK using the halo2 library.

## Description

The goal is to create an implementation of the BLAKE2f algorithm as a zk-SNARK using the halo2 library.

## Features

- Utilizes the halo2 library for creating zk-SNARKs
- Implements the BLAKE2f hash algorithm

## Tasks

During the development process, the following tasks need to be addressed:

- [ ] Understand the bitchunk spread
- [ ] Understand why r1 and r2 are used in lookup
- [ ] Fix XOR operations in compression_gate
- [ ] Implement lookup for XOR operations in the compression function
