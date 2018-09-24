This is a spring cloud config git development uri file.

并且其中需要在config中被管理的配置文件是需要遵守命名规范的，并且如果是server端，验证访问，本例中http://localhost:8888/auther/dev
其中auther是配置文件中的key,dev代表的是配置文件名称后面的-dev,表示哪个配置文件。

/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties
