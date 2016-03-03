<!---
# license: Licensed to the Apache Software Foundation (ASF) under one
#         or more contributor license agreements.  See the NOTICE file
#         distributed with this work for additional information
#         regarding copyright ownership.  The ASF licenses this file
#         to you under the Apache License, Version 2.0 (the
#         "License"); you may not use this file except in compliance
#         with the License.  You may obtain a copy of the License at
#
#           http://www.apache.org/licenses/LICENSE-2.0
#
#         Unless required by applicable law or agreed to in writing,
#         software distributed under the License is distributed on an
#         "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
#         KIND, either express or implied.  See the License for the
#         specific language governing permissions and limitations
#         under the License.
-->

# Cordova WebRTC plugin

[WebRTC](https://webrtc.org/) is a free,
open project that provides browsers and mobile applications
with Real-Time Communications (RTC) capabilities via simple APIs.
The WebRTC components have been optimized to best serve this purpose.

```sh
cordova plugin add https://github.com/yfix/yfrtc.git
```

## Sample App

```sh
npm install -g bower grunt-cli
npm install -g cordova ios-sim

cordova create [name-app] [com.name.app] [NameApp]
cordova platform add ios@3.9
cordova platform add android
cordova platform add browser --usegit
cordova plugin add org.apache.cordova.console
cordova plugin add https://github.com/yfix/yfrtc.git
cordova prepare ios
cordova prepare android
```
