# api service
build by gradle,use junit,springmvc,mybatis,groovy

##api接口规范
采用Restful规范
##javadoc规范
* 类名要注明作者(<font color="red">@author</font>，逗号分割)及版本号(<font color="red">@version</font>),并说明类具体功能
* 类中常量需要用<font color="red">@value</font>进行说明
* 方法名需要注明输入参数(<font color="red">@param</font>)和返回数据(<font color="red">@return</font>),如有异常抛出，但需要注明异常内容(<font color="red">@exception</font>)
* 类或者方法过期后不再使用时，需要用<font color="red">@deprecated</font>进行注明

## build
<code>gradle build</code>

## test
<code>gradle test</code>

## dev run
<code>gradle jettyRun</code>

<code>http://localhost:10086/openexpense</code>


