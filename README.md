# WIN-WHL
个人编译windows环境下的一些python包，主要是机器学习相关的。借助github action，就可以避免在本地搞VS环境，何乐而不为呢？欢迎star和fork！

请在Action里面找你想要的wheel包

目前已支持：
- [fairseq](https://github.com/facebookresearch/fairseq): python 3.10, 3.11, 3.12
    > 原生预编译的版本为3.8，编译时对pip版本有要求
- [lightgbm](https://github.com/microsoft/LightGBM)
    > 仅作练习。实际上用`conda install lightgbm`就能自动安装gpu版本了，没有必要额外编译。见[doc](https://github.com/microsoft/LightGBM/tree/master/python-package#install-from-conda-forge-channel)

> [!note]
> 你可以fork本仓库，然后在自己的github上使用action功能，点击按钮就能生成最新的包构建的wheel。