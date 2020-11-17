# Floyd Q - Exynos8890
* BUG reports repo for [LeeXDA_Rom](https://bit.ly/3cEpe0N)

Full permission to use from @Anan1211 @xda-developers.

#### How to write issues

* Select right template for your Issue request `([BUG] for bug, [Request] for requests)`
* Please explain your issue correctly
* Give as much details as possible.
* Low effort issues most likely will be closed.
* Gather logs!

#### How to gather logs with **LoggingKit**
* Clone/Fork the Repo or Download the kit via [Releases](https://github.com/Lethany/LeeXDA_Rom_Reports/releases)
#### [With booted System] - **Intended for Crashes, FCs and other SYSTEM Logs**

1) For Windows users: Install **Universal ADB drivers** or **Brand specific ADB drivers** if you don't have them
    For Linux and macOS users: To make the files executable, type in Terminal `chmod +x` and drag the files
2) In your phone **Enable USB debugging** under `Developer options`
3) Launch your needed log type
4) Grant `ADB Keys`
5) Close your log type
6) Launch the needed log, again
7) After recording log, attach the created file to your GitHub issue post.

#### **Legend**

- [x] log-ball			= Full buffer logcat. Don't use unless requested
- [x] log-all 			= Verbose logcat, messy but records everything
- [x] log-e 			= Log for Error filter, Only shows crashes
- [x] log-ril 			= Log for Modem/SIM and other RIL issues
- [x] log-kmsg			= Log for Kernel msg when the kernel panics
- [x] log-dmsg			= Log for Kernel on an active system
- [x] log-ActiveDmesg 	= Looping Log for Kernel on Active sysetm

* Being stuck at **`"Waiting For Device"`** means you either **did not auth the adb key** or your **device does not even have debugging enabled**
* **Extra**: You can skip step 3/4 by running **`ADB_Keys.bat`** if you previously allowed your computer ADB
