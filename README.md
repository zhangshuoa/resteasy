# resteasy
3.6.2简介初读

## 总揽
* jboss开发的，基于JAX-RS API的规范。
* 在WildFly（和tomcat、weblogic、Jetty一样的web容器）中，得到了更多的集成。


## 章节简介
* 3.3. Deploying to other servlet（not wildfly） containers
  * 3.0 版本的servlet
  * 之前的servlet
* 3.4 配置开关
* 3.5 javax.ws.rs.core.Application
  * 这是一个标准的JAX-RS类。
  * If your web.xml file does not have a <servlet-mapping> element, you must use an Application
class annotated with @ApplicationPath.
