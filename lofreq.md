### lofreq：A sequence-quality aware, ultra-sensitive variant caller for NGS data（https://github.com/CSB5/lofreq）

开发语言：C
安装命令：
1. wget -c https://github.com/CSB5/lofreq/archive/refs/tags/v2.1.5.tar.gz
2. tar -zxvf v2.1.5.tar.gz
3. cd lofreq-2.1.5
4. ./bootstrap
5. ./configure --with-htslib=/path/htslib --prefix=/path/lofreq
6. make && make install
