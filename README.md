  Cameleonica filesystem
==========================

Cameleonica is a **safe cryptographic steganographic advanced filesystem**. It aims to guarantee confidentiality, authenticity, plausible deniability, transactions, snapshots and versioning, instantaneous copying, permanent deletion, high performance and low delays, compression, and hashing.

Further design will include a FUSE frontend and Nautilus extension. Secure cryptographic schemes will be used such as AES, Salsa20, SHA-2, SHA-3, scrypt, CTR mode, GCM authenticated encryption, /dev/urandom, CryptGenRandom. Internally extents, copy on write, ring buffers of discrete updates, complete inodes, and deniably encrypted pointers will be used.

  Project status and roadmap
------------------------------

Project will remain in EXPERIMENTAL phase for several months. Only initial ideas have been written down so far. Please be patient, there will be more documentation published with time. You can read:

- [Mission statement](documentation/mission.pdf) (6 pages)

There is no code yet. Further designs will be written down before anything runnable is created. 

  Development notice
----------------------

Code will be developed in Python/Cython. Documentation is created in LibreOffice writer and XMind mind mapping tool. User experience design is done in Glade.

Referenced documentation is a local copy of published material, good read saved for future need. There are also some random notes, you can just ignore them. Deprecated C# code was put away but kept for reference. It will be removed in the future when real code is more mature. 

License is set to MIT Licence, unless something changes.

