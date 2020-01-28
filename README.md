# WearProxy
Proxy (on boot) For Wear OS!

# Install :
adb install WearProxy.apk
Press "Allow" or "Always allow this Computer".

# Permissions "edit & activate :
adb shell pm grant marsdroid.me.wearproxy android.permission.WRITE_SECURE_SETTINGS

# Permissions "remove & delete" :
adb shell settings delete global http_proxy; adb shell settings delete global global_http_proxy_host; adb shell settings delete global global_http_proxy_port; adb shell settings delete global global_http_proxy_exclusion_list; adb shell settings delete global global_proxy_pac_url; adb shell reboot
