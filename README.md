# sway-ecc
ECC operations using sway Op-codes

- This repo currently uses the ecc opcodes from the feature/zk-opcodes branch of sway: https://github.com/FuelLabs/sway/tree/feature/zk-opcodes
- Instruction set: https://github.com/FuelLabs/fuel-specs/blob/abfd0bb29fab605e0e067165363581232c40e0bb/src/fuel-vm/instruction-set.md

## Building and testing
Since this repo uses the feature/zk-opcodes branch opcodes of sway, in order to build one need to first build feature/zk-opcodes branch of sway and then run:

- Build: `./<path_to_your_sway_repo>/target/debug/forc build`
- Test: `./<path_to_your_sway_repo>/target/debug/forc test`