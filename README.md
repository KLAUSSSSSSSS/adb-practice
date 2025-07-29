## 1: Device Info
adb shell getprop ro.product.model
adb shell getprop ro.build.version.release
##2: Capture logs
adb logcat -d > logcat.txt
## 3:Filter error logs
adb logcat *:E > error_logs.txt
## 4: Pull file from device
adb pull /sdcard/Download/cavli_c10qm_at_command_manual_erv_1.9.pdf
