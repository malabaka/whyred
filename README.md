# whyred在AndroidManifest.xml文件中添加权限声明：
xml
复制代码
<uses-permission android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
在AndroidManifest.xml文件中注册BroadcastReceiver
xml
复制代码
<receiver android:name=".BootBroadcastReceiver">
    <intent-filter>
        <action android:name="android.intent.action.BOOT_COMPLETED" />
    </intent-filter>
</receiver>
创建名为BootBroadcastReceiver的BroadcastReceiver，并重写onReceive()方法，在该方法内实现APP的自启动逻辑。
java
复制代码
public class BootBroadcastReceiver extends BroadcastReceiver {
    @Override
    public void onReceive(Context context, Intent intent) {
        if (Intent.ACTION_BOOT_COMPLETED.equals(intent.getAction())) {
            // TODO: 实现 APP 的自启动逻辑
        }
    }
}
需要注意的是，自启动功能会影响手机的性能和电量消耗，建议谨慎使用
