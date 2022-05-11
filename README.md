# cache_coherence

- MOESI_HTM: 在MOESI的基础上加入了HTM的一些状态和
- GPU_VIPER: GPU使用 VI-WT协议, L3使用MOESI协议
- AMD Hammer-like protocol: L1 和 L2共用一个controller，并且是exclusive
- MESI_Two_level_Aladdin: 在L1使用的是MESI协议，但是在L2为了兼容ACP请求，增加了一些状态和事件。
- Denovo: 在L2把MESI和Denovo进行合并[Efficiently Supporting Dynamic Task Parallelism on Heterogeneous Cache-Coherent Systems](https://www.csl.cornell.edu/~cbatten/pdfs/wang-hcc-dts-isca2020.pdf)

