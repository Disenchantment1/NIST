# NIST

存储 NIST 检测内容以及检测文件和结果信息

NIST 检测下载地址：https://csrc.nist.gov/projects/random-bit-generation/documentation-and-software

TestFile 文件夹：
  - M ：使用 AIVF 编码直接压缩 bible.txt 文件得到的码字序列
  - C1：使用 AIVF 线性变换码字压缩加密 bible.txt 文件得到的码字序列
  - C2：使用 AIVF 多种码字映射压缩加密 bible.txt 文件得到的码字序列

TestResult 文件夹：
  M，C1，C2 开头表示对应的码字序列检测结果
  10，100，1000 表示将整个序列分成不同的子序列的个数，每个子序列 $\lfloor\frac{\text{totalBits}}{n}\rfloor$
