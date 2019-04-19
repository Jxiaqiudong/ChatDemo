注意：在导入leancloudchatkit包的步骤
1、将文件夹 leancloudchatkit 复制到 ChatDemo 根目录；
2、修改 ChatDemo/settings.gradle 加入 include ':leancloudchatkit'；
3、修改 ChatDemo/app/build.gradle，在 dependencies 中添加 compile project(":leancloudchatkit")
4、修改 
   // LeanCloud 基础包（将数字前的v去掉，如：v4.7.10改为4.7.10）
    implementation 'cn.leancloud.android:avoscloud-sdk:v4.7.10'
    // 推送与即时通讯需要的包
    implementation('cn.leancloud.android:avoscloud-push:v4.7.10@aar') { transitive = true }
5、将build.gradle中的 SDK（包括compileSdkVersion、 minSdkVersion、 targetSdkVersion）修改为相应的版本。