## rtc-terminal (CLI)

1. Install rtc-ssh on remote device/server from the repository: https://github.com/mxseba/rtc-ssh

Note the uuid key generated in the rtc-ssh application.

2. Get source rtc-terminal on local computer using the Go compilator:
```
go get -u github.com/mxseba/rtc-terminal
cd $GOPATH/bin
rtc-terminal -uuid=<UUID key remote device>
```
Option <code>-uuid</code> usage only first run, the uuid key will be saved automatically in the config.ini file.

### Install from binary
https://github.com/mxseba/rtc-terminal/releases

Rtc-SSH uses the pion-WebRTC library: https://github.com/pion/webrtc
