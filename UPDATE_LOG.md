#Blade 更新日志

### v1.2.6
	1. 添加多重路由配置方式

### v1.2.5
	1. 添加JSON、Properties文件配置
	2. 优化代码性能
	3. 去除内置jetty服务
	
### v1.2.2
	1. `DateKit`添加获取当前unix时间戳
	2. 修复`blade-sql2o`分页bug
	3. 修复`blade-beetl`没有存储`ModelAndView`的数据
	
### v1.2
	1. 修复sql2o更新Bug
	2. 去除blade-kit无用类
	3. 添加邮件支持
	4. 添加程序计时支持
	5. 添加http网络请求支持
	6. 优化内置日志输出
	7. 添加定时任务支持
	8. 重构项目结构
		
### v1.1.x
	1. 去除对外公开的多余方法展示
	2. 添加`Blade.run()`方式运行jetty
	3. 添加`Blade.register()`方法注册bean对象
	4. 优化IOC对象管理
	5. 优化底层IO
	6. 简化插件扩展
	7. 拦截器路由匹配分离
	8. 修复jetty在多maven环境下运行bug 
	9. 添加初始化监听context
	10. 优化文件上传
	11. 优化路由匹配
	12. 添加方法执行监测
	13. 添加缓存支持

### v1.0.0
	第一个稳定版本发布