# 6.5.1.10版本
1. 修复sdist打包缺失lib文件的问题

# 6.5.1.9版本
1. 调整接口初始化时，接口名称的赋值方式
2. 将动态库的链接模式由默认的动态的MD改为静态的MT
3. 增加对于socks代理的支持

# 6.5.1.8版本

1. 修复遇到非大商所的ActionDay字段为空的合约行情推送会报错的问题
2. 调整安装脚本setup.py，支持Windows下安装时根据Python版本进行编译