# android-gradle

### gradle-dependencies
常用的gradle依赖


### Nexus

##### 配置Nexus参数
> NEXUS_USERNAME=username <br>
 NEXUS_PASSWORD=password
 NEXUS_REPOSITORY_URL=http://xxx/nexus/content/repositories/xxx/

 ##### 引入upload脚本
 > apply from: 'https://github.com/rushcoder/android-gradle.git/nexus_upload.gradle'

 ### artifactory
 > artifactory_username=admin
artifactory_password=lestar123456
artifactory_url=http://localhost:8081/artifactory