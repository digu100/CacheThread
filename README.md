ThreadCache:

ThreadCache is a high-performance, multithreaded in-memory cache system implemented in C, designed to efficiently handle concurrent access from multiple threads while maintaining data integrity. It mimics the behavior of real-world caching mechanisms like those used in operating systems and databases, emphasizing thread safety, memory management, and performance under load.

The core of the system is a thread-safe key-value store with fixed-size memory blocks. It supports:

Concurrent insertion and lookup by multiple threads

An LRU (Least Recently Used) eviction policy to manage limited cache space

Fine-grained mutex locks for safe access to shared memory

Configurable parameters for block size, number of threads, and cache capacity

ThreadCache was built to explore how low-level systems manage concurrent access and memory efficiency. It provides a controlled simulation of how caching behaves in multi-core environments
