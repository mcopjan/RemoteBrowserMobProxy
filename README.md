# RemoteBrowserMobProxy

This is a netstandard2.0 client library to communiate with BrowserMobProxy server API described at https://github.com/lightbody/browsermob-proxy

Example of usage (Docker needs to be installed):
- Run the [compose.ps1](./compose.ps1) powerhell script to prepare selenium hub, node and the proxy
- See example of communication with browsermobproxy docker container [RemoteBrowserMobProxyFunctionalTests.cs](./RemoteBrowserMobProxy.Tests/RemoteBrowserMobProxyFunctionalTests.cs)

[![NuGet](https://www.nuget.org/Content/gallery/img/logo-header-94x29.png)](https://www.nuget.org/packages/RemoteBrowserMobProxyNetStandard/)
![.NET](https://github.com/mcopjan/RemoteBrowserMobProxy/workflows/.NET/badge.svg?branch=master)
