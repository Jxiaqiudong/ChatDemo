ע�⣺�ڵ���leancloudchatkit���Ĳ���
1�����ļ��� leancloudchatkit ���Ƶ� ChatDemo ��Ŀ¼��
2���޸� ChatDemo/settings.gradle ���� include ':leancloudchatkit'��
3���޸� ChatDemo/app/build.gradle���� dependencies ����� compile project(":leancloudchatkit")
4���޸� 
   // LeanCloud ��������������ǰ��vȥ�����磺v4.7.10��Ϊ4.7.10��
    implementation 'cn.leancloud.android:avoscloud-sdk:v4.7.10'
    // �����뼴ʱͨѶ��Ҫ�İ�
    implementation('cn.leancloud.android:avoscloud-push:v4.7.10@aar') { transitive = true }
5����build.gradle�е� SDK������compileSdkVersion�� minSdkVersion�� targetSdkVersion���޸�Ϊ��Ӧ�İ汾��