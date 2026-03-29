C++ and Rust implementations for Intel and AMD of CRC64-nvme, the 64-bit cyclic redundancy check. Timed at 17GB/sec C++, 16GB/sec Rust singlethreaded for large inputs. It makes an effort to be fast for small inputs too. It uses SIMD instructions. This is bitwise compatible with the 64-bit CRC used by Microsoft Azure and Cosmos. Microsoft wanted a good implementation of that CRC to be publicly available. The C++ has a mediocre implementation for non-AMD-or-Intel as well.

Documentation: https://burtleburtle.net/bob/hash/crc.html .
