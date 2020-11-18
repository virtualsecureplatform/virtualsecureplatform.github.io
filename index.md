We present Virtual Secure Platform (VSP), the first comprehensive platform that implements a multi-opcode general-purpose sequential processor over Fully Homomorphic Encryption (FHE) for Secure Multi-Party Computation (SMPC). VSP protects both the data and functions on which the data are evaluated from the adversary in a secure computation offloading situation like cloud computing. We proposed a complete processor architecture with a five-stage pipeline, which improves the performance of the VSP by providing more parallelism in circuit evaluation. In addition, we also designed a custom Instruction Set Architecture (ISA) to reduce the gate count of our processor, along with an entire set of toolchains to ensure that arbitrary C programs can be compiled into our custom ISA. In order to speed up instruction evaluation over VSP, CMUX Memory based ROM and RAM constructions over FHE are also proposed. Our experiments show that both the pipelined architecture and the CMUX Memory technique are effective in improving the performance of the proposed processor. We provide an open-source implementation of VSP which achieves a per-instruction latency of less than 1 second. We demonstrate that compared to the best existing processor over FHE, our implementation runs nearly 1,600× faster.

- [GitHub](https://github.com/virtualsecureplatform/kvsp)
- [arXiv](https://arxiv.org/abs/2010.09410)
- [30th USENIX Security Symposium prepublication](https://www.usenix.org/conference/usenixsecurity21/presentation/matsuoka)

## Demo on YouTube

<iframe width="640" height="365" src="https://www.youtube.com/embed/1YsUaZMITR8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Japanese Resouces

- カーネル/VM探検隊@関西 10回目 (in Japanese)
  - [Slides](https://speakerdeck.com/nindanaoto/development-of-virtual-secure-platform)
  - [Video](https://youtu.be/J-pF4fg3r04?t=6254)
- 【2019年度未踏／No.15】準同型暗号によるバーチャルセキュアプラットフォームの開発 (in Japanese)
    - [Abstract](https://www.ipa.go.jp/jinzai/mitou/2019/gaiyou_s-4.html)
    - [Video](https://youtu.be/apCbAPt7r3I)
    - [Report](https://github.com/virtualsecureplatform/MitouDocument)
