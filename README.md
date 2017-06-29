#  DevOps初尝-自动化部署APP

#### 效果

>  在本地用 `git push` 上远程github仓库的时候，自动把代码build一次且部署到相应的服务器上

Steps:
1. 本地修改代码
2. Push到github
3. 泡杯java
4. 服务器自动部署完成

![结果截图](gif/result.gif)

#### 实现技术栈

Cloud  | OS | Continuous Tools | SCM | App|
-------|----|------------------|-----|----|
![Aliyun](icon/aliyun.png)|![Ubuntu](icon/ubuntu.png)|![Docker](icon/docker.png)**+** ![Jenkins](icon/jenkins.png)|![Git](icon/git.png)**+** ![Github](icon/github.png)|![Nodejs](icon/nodejs.png)**+** ![vue_angular_react](icon/vue_angular_react.png)|

#### 好处

- 团队开发
 - 多人异地，同时对产品不同阶段进行开发
 - 随地办公的基础
  
- 分发
 - 不同阶段的服务器同时部署，持续交付
