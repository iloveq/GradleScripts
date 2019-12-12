# GradleScripts
gradle 脚本合集

##### gradle-task-time-counter 统计每个 gradle task 的执行时间 选择优化
将 gradle-task-time-counter.gradle 放在 gradle 目录下 在工程的 build.gradle 下引入插件
apply from: rootProject.file('gradle/gradle-task-time-counter.gradle')
