"# platform_frameworks_base" 
<br><br>
Changes in to disable android power features (commented out):<br>
core/java/com/android/internal/os/BatteryStatsImpl.java<br>
core/java/com/android/internal/os/KernelWakelockReader.java<br>
services/core/java/com/android/server/BatteryService.java<br>
services/core/java/com/android/server/am/BatteryStatsService.java<br>
services/core/java/com/android/server/power/PowerManagerService.java<br>
services/core/jni/com_android_server_power_PowerManagerService.cpp<br>
<br>
If required to compared the changes, can refer to <br>
https://android.googlesource.com/platform/frameworks/base/ <br>
Under r2 branch
