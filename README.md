jutils
在java编码过程中我们可能会遇到各种各样的util，jutils是LZ在编程过程中总结的工具类，包括：基础工具类（时间、正则表达式、字符串、随机数等等），excel解析生成、word解析生成、文件操作、图片操作、敏感字、加解密等等。

特性
1、功能齐全，有你所想。

2、简单易用，无学习成本。

主要功能
package:base--基本功能
ConverUtils：转换工具类，主要应用于各种类型之间的转换

IdCardValidator:身份证校验工具类，提供较为精确的身份证校验

MoneyUtils:金钱处理工具类

RegexUtils:正则表达式工具类，验证数据是否符合规范

StringUtils:字符串工具类，对字符串进行常规的处理

ValidateHelper: 判断对象、字符串、集合是否为空、不为空

package:clone--克隆
CloneUtils:克隆工具类，进行深克隆,包括对象、集合

date：时间类
DateFromatUtils：格式转换工具类

DateUtils:日期、时间工具类

TimestampUtils：timeStamp工具类

package:encrypt--加解密
EncryptAndDecryptUtils：加解密工具类唯一入口

AESUtils:AES加解密工具类

Base64Utils:base64加解密工具类

DESUtils：des加解密工具类

MD5Utils：md5、SHA加解密工具类（根据转换器参数不同，现在不同的加密方式）

package:excel--excel
ExcelExportHelper:Excel 生成通用类，为了兼容，所有 Excel 统一生成 Excel2003 即：xx.xls

ExcelReadHelper:解析Excel，支持2003、2007

package:file--文件处理
FileUtils:文件处理工具类

ZipUitls:ZIP工具类

package:ImageUtil--图像处理
ImageUtil:图像处理。对图片进行压缩、水印、伸缩变换、透明处理、格式转换操作

math：数字类
BigDecimalUtils：BigDecimal工具类

RandomUtils:随机数工具类

QRCode：二维码类
MatrixToImageCofig：二维码配置

MatrixToImageWriter:二维码工具类

sequence：序列
GenerateSequenceUtils：生成唯一的序列

package:sensitiveword--J敏感词
SensitivewordFilterUtil:铭感词过滤工具类

SensitiveWordInit:初始化敏感词库，将敏感词加入到HashMap中，构建DFA算法模型

word：word类
