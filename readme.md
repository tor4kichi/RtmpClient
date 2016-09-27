# RtmpClient for Windows Runtime

[![NuGet](https://img.shields.io/nuget/v/RtmpClient.UWP.svg?style=flat-square)](https://www.nuget.org/packages/RtmpClient.UWP/) 
[![License](https://img.shields.io/github/license/tor4kichi/RtmpClient.svg?style=flat-square)](https://github.com/tor4kichi/RtmpClient/blob/master/license.md)

This client treats rtmp streaming, just like Adobe Flash Player. Now, only rtmp is available.

(this is modified to uap10.0 build from origianl RtmpClient.)

## Environment
You can use:

- ~~Windows (8.1),~~
- ~~Windows Phone (8.1).~~
- UWP

## License
This component and demoapp is “2-clause BSD license.”
You must check “[license.md](./license.md).”

## API reference
If you know these in detail, you check “[Document](./Document/)” folder. However, this file is not latest!

## Beta version Phase II
This component is debugged with Windows 8.1 and Windows Phone 8.1 Emulator. However, implementation of error or exit transaction is not completed.

Thus, this component sometimes changes API endpoints.

## TODO
- rtmps/rtmpt/rtmpe streaming handle
- SharedObject handle
- more useful, just like callback assigns parameter.
- and so on…

## Related projects
- [Action Message Format for Windows Runtime](//github.com/mntone/Data.Amf)
- [Action Message Format for UWP](//github.com/tor4kichi/Data.Amf)