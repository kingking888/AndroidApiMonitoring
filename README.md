# AndroidApiMonitoring

### Installation

- install virtualenv

```shell
pip install virtualenv
```

- install requirements

```shell
pip install -r requirements
```

- adb in path file 
- emulator/device already running and connect

### Usage

```shell
 python frida_monitoring.py -f app.apk api.txt
 python frida_monitoring.py package_name resources\api_frida_test.txt
```