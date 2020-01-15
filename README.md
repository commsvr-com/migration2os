# `CommServer` software Migration and Maintenance

This project is aimed at `CommServer` software migration from on-premise subversion repository to GitHub and publishing it as the Open-source software (OSS). OSS is a type of computer software in which source code is released under a license in which the copyright holder grants users the rights to study, change, and distribute the software to anyone and for any purpose.

The project will be used to manage the migration process of transferring multi-parts software from an on-premise subversion repository to a set of GitHub repositories.

After migration, this project will aggregate the description of all activities addressing the software maintenance process.

## About `CommServer`

`CommServer` is a package of software to manage data transfer. Built-in technologies and algorithms provide a smart data transmission that automatically adapts its parameters to the process needs and underlying communication network capabilities.

To learn more about `CommServer` software family visit the [software home page][comsvr].

The `CommServer` software was written by CAS Lodz Poland. I am the founder and Executive Director of CAS. Now CAS is just an individual business activity conducted by me, so I decided to move this software to Open Source.

## Migration Scope

- [ ] CAS.Windows (#11)
- [ ] CAS.Windows.Forms (#12)
- [x] [commsvr-com/Help](https://github.com/commsvr-com/Help) contains CAS.MAML
- [x] [PR34-Documentation](https://github.com/commsvr-com/Documentation)
- [x] [RealTime][RealTime] - Real-Time Programming Helpers Library.
- [x] [CodeProtect][CodeProtect] - Helper library supporting licenses creation and validation.
- [x] [ASMD][ASMD] - OPC UA Address Space Model Designer
- [x] [OPC-UA-OOI.ConfigEditor][OPC-UA-OOI.ConfigEditor] - Object Oriented Internet Reactive Networking Configuration Editor
- [x] [ProcessObserver][PO] - Object-Oriented Internet Machine to Sensors Connectivity (OOI.M2S)
- [ ] CommServer.DataProvider - selected protocol drivers, i.e. MODBUS, M-BUS, S-BUS, etc. simulators
 diagnostic tool (#10)
- [x] [CommServer => mpostol/PO.Common][PO.Common]

> NOTE CAS.MAML and PR34-Documentation requires installation of the SHFB tool to process MAML files.

## Releases

We use [Semantic Versioning](http://semver.org/) for versioning. For the versions available, see the [releases on this repository](https://github.com/commsvr-com/migration2os/releases). For your convenience, the versions of the tools and NuGet packages making up the `CommServer` software has been listed in the next subsections.

### Tools

The table below lists the latest versions of the published Tools.

| Description | Version |Source|Installer|
|-------------|:-------:|------|------------|
| Public release of the ASMD | 4.1 | [mpostol/ASMD][ASMD] | [OOI - OPC UA Address Space Model Designer V 4.1](https://github.com/mpostol/ASMD/releases/tag/4.1.0) |
CAS Address Space Model Designer (ASMD) |3.20.1|[mpostol/ASMD][ASMD]|[Windows installation released by CAS (V3.20.1 -2016)](http://www.commsvr.com/COInstal/UAModelDesignerPro/setup.exe)
Object Oriented Internet Reactive Networking Configuration Editor| NA |[mpostol/OPC-UA-OOI.ConfigEditor][ConfigEditor] | NA

### NuGet packages

The table below lists the published NuGet packages.

| Package Id  | Description | Source |
|-------------|-------------|:------:|
[CAS.CodeProtect](https://www.nuget.org/packages/CAS.CodeProtect/) |Helper library supporting licenses creation and validation.| [mpostol/CodeProtect](https://github.com/mpostol/CodeProtect)
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

## Read more

- [Object Oriented Internet - C# deliverables supporting a new Machine To Machine (M2M) communication architecture; GitHub repository][OOI]
- [OPC UA Address Space Model Designer;GitHub repository](ASMD)
- [CommServer - Home Page][comsvr]
- [CAS Lodz Poland Home Page][CAS]
- [My Blog: About enablers of future solutions](http://wwww.mpostol.wordpress.com/)
- [About me on LinkedIn](https://pl.linkedin.com/in/mpostol)
- [OPC Foundation](https://opcfoundation.org/)
- [Contributing](https://github.com/commsvr-com/migration2os/blob/master/CONTRIBUTING.md)
- [Process Observer as a Platform For Large Scale Distributed Process and Business Management Integration][POCommSvr]

[CodeProtect]: https://github.com/mpostol/CodeProtect
[ConfigEditor]: https://github.com/mpostol/OPC-UA-OOI.ConfigEditor
[CAS]:http://www.cas.eu/
[comsvr]:http://www.commsvr.com/
[asmdn]:https://github.com/mpostol/ASMD/tree/master/_nugets
[OOI]:https://github.com/mpostol/OPC-UA-OOI
[ASMD]:https://github.com/mpostol/ASMD
[PO]:https://github.com/mpostol/ProcessObserver
[POCommSvr]:http://www.commsvr.com/DownloadCenter/Publications/IdeaofProcessObserver.aspx
[OPC-UA-OOI.ConfigEditor]:https://github.com/mpostol/OPC-UA-OOI.ConfigEditor
[RealTime]: https://github.com/mpostol/RealTime
[PO.Common]:https://github.com/mpostol/PO.Common

<?-

## Content

### Architecture

The repository workspace are organized as it is illustrated in the Figure below.

TBD

## How to Contribute

TBD

-->
