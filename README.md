# `CommServer` software Migration and Maintenance

This project is aimed at `CommServer` software migration from on-premise subversion repository to GitHub and publishing it as the Open-source software (OSS). OSS is a type of computer software in which source code is released under a license in which the copyright holder grants users the rights to study, change, and distribute the software to anyone and for any purpose.

The project will be used to manage the migration process of transferring multi-parts software from an on-premise subversion repository to a set of GitHub repositories.

After migration, this project will aggregate the description of all activities addressing the software maintenance process.

## About `CommServer`

`CommServer` is a package of software to manage data transfer. Built-in technologies and algorithms provide a smart data transmission that automatically adapts its parameters to the process needs and underlying communication network capabilities.

To learn more about `CommServer` software family visit the [software home page][comsvr].


The `CommServer` software was written by CAS Lodz Poland. I am the founder and Executive Director of CAS. Now CAS is just an individual business activity conducted by me, so I decided to move this software to Open Source.

## Migration Scope

- [ ] [Address Space Model Designer](http://www.commsvr.com/Products/OPCUA/UAModelDesigner.aspx)
- [ ] [Process Observer](http://www.commsvr.com/Products/OPCUA/CommServerUA.aspx)
  - [ ] communication engine used by OPC servers
  - [ ] configuration tool
  - [ ] monitoring tool
  - etc.

## Releases

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions available, see the [releases on this repository](https://github.com/commsvr-com/migration2os/releases). For your convenience, the versions of the tools and NuGet packages making up the `CommServer` software has been listed in the next subsections.

### Tools

The table below lists the latest versions of the published Tools.

| Description | Version |Source|Installer|Date|
|-------------|:-------:|------|------------|----|
|Address Space Model Designer (ASMD) |3.20.1|[mpostol/ASMD](mpostol/ASMD)|[Windows installation released by CAS](http://www.commsvr.com/COInstal/UAModelDesignerPro/setup.exe)|May 17, 2016|

### NuGet packages

The table below lists the published NuGet packages.

| Package Id  |  Description |Repository|
|-------------|--------------|:--------:|
[CAS.CodeProtec](https://www.nuget.org/packages/CAS.CodeProtect/) |Helper library supporting licenses creation and validation.| [mpostol/CodeProtect](https://github.com/mpostol/CodeProtect)
[CAS.RealTime][asmdn]|Real-Time Programming Helpers Library. |[mpostol/RealTime](https://github.com/mpostol/RealTime)
[CAS.CommServer.DA.Client][asmdn] | Provides set of assemblies that may be used by the OPC DA Clients. | NA|
[CAS.CommServer.DA.Viewer][asmdn]|CommServer OPC Viewer is a full featured OPC client designed to help during installation, testing, and configuration of OPC Data Access compliant servers. This tool is available as standalone or included in the other software packages.|NA
[CAS.CommServer.DAClientConfiguration][asmdn]|Library supporting OPC Classic Configuration management functions.|NA
[CAS.CommServer.DAServerConfiguration][asmdn]|Server Configuration Management Library provides CAS.NetworkConfigLib namespace.|NA
[CAS.CommServer.DeviceSimulator][asmdn]|Device Simulator for CommServer family.|NA
[CAS.CommServer.OPCClassic.SDK.COMWrapper][asmdn]|The COM Wrapper library for OPC Classic .NET API based on OPC Foundation SDK 2.01.106.|NA
[CAS.CommServer.OPCClassic.SDK.Core][asmdn]|The Core library for OPC Classic .NET API based on OPC Foundation SDK 2.01.106.|NA
[CAS.CommServer.UA.ConfigurationEditor.ServerConfiguration][asmdn]|This plug-in is used to configure the CAS OPC UA CommServer and define bindings of the model instance nodes with the actual real-time process data source.|NA
[CAS.CommServer.UA.ModelCompiler.Command][asmdn]|The Model Compiler generates UANodeSet, C# and ANSI C source code from XML files which include the UA Services, data-types, error codes, etc.; and numerous CSV files that contain NodeIds, error codes, and attributes etc. To be used as a plug-in by the CAS Address Space Model Designer.|NA
[CAS.CommServer.UA.ModelCompiler.Common][asmdn]|OPC UA ModelCompiler common part separated form the CAS.CommServer.UA.ModelCompiler to provide the standard model.|NA
[CAS.CommServer.UA.Stack.Core][asmdn]|OPC UA Stack provided by OPC Foundation and refactored by CAS.|NA
[CAS.Licenses.Container][asmdn]|Is deprecated and will be removed from the dependence's chain|NA
[CAS.MAML.HelpTopics.Content][asmdn]|Library containing schema definition of the all topics xml file.|NA
[CAS.UA.Common][asmdn]|The library contains a shared helpers used to process OPC UA data. It contains Types definition and serialization classes.|NA
[CAS.UA.IServerConfiguration](https://www.nuget.org/packages/CAS.UA.IServerConfiguration/)|The CAS.UA.IServerConfiguration library contains a shared interfaces for server configuration which UA applications can reference.The library provides an abstraction over any OPC UA server configuration plug-in. Using the library allows an application to indirectly access the server configuration attributes without relying on hard references. The hope is that using this library, third-party applications and frameworks can begin to leverage server configuration management without tying themselves down to a specific implementation.|[mpostol/OPC-UA-OOI](https://github.com/mpostol/OPC-UA-OOI)
[CAS.Windows.Forms][asmdn]|The library contains Windows.Forms controls.|NA

[comsvr]:http://www.commsvr.com/
[asmdn]:https://github.com/mpostol/ASMD/tree/master/_nugets

<?-
## Content

### Architecture

The repository workspace are organized as it is illustrated in the Figure below.

TBD

## How to Contribute

TBD

## See Also

TBD

-->
