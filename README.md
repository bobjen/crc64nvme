C++ and Rust implementations for Intel and AMD of CRC64-nvme, the 64-bit cyclic redundancy check. Timed at 17GB/sec C++, 16GB/sec Rust singlethreaded for large inputs. It makes an effort to be fast for small inputs too. It uses SSE intrinsics.

Documentation: https://burtleburtle.net/bob/hash/crc.html .
