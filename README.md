# 工具类   基础组件

### common-base:
1. 异常基类
2. 服务接口返回DTO

### common-dao:
1. Dao基类，基本方法实现
2. 所有Dao必须继承此类

### common-dependencies:
1. 基础组件依赖统一管理

### common-dynamic-log-level:
1. 日志等级动态调整
```bash
logging.level.${package} = warn
```
- [x] 支持Apollo
- [ ] 支持HTTP

### common-http-wrapper:
1. 包装HttpServletRequest 可重复获取body
```bash
使用方法
HttpServletRequest httpServletRequest= (HttpServletRequestBodyReaderWrapper) request;
```

### common-mq:
1. RabbitMq 封装
2. 直接配置参数即可使用

### common-mongodb:
1. Mongodb 封装,支持多数据源及连接池

### common-trace:
1. 日志跟踪组件,logback 加入 %X{traceId}
2. 非HTTP触发的方法添加@Trace注解

### common-redis:
1. Redis封装

### common-utils:
1. 常用方法封装
   * String 常用
   * Date 常用计算，格式等
   * List 常用的转换以及切分
   * HttpClient
   * Excel导出
   * Bean copy
   * Md5
   * 密码验证
   * 随机数
   * 序列化，反序列化
   * TreeId 计算生成
   * XML 生成及解析

### common-validation:
1. 参数验证


### mybatis-plugins:
1. mybatis 插件，生成Bean时可以选择配置

### server-explorer
1. 后台管理服务接口
2. 后台管理服务工厂
3. 后台管理服务策略
4. 多语言处理

### server-explorer-expand
1. 后台管理服务唯一检查
2. 后台管理服务模板方法

### server-frame
1. 后台服务通用接口

### common.ocr
1. ocr识别
2. 身份证
3. 驾驶证
4. 行驶证
