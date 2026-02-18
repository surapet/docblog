When setting up a Windows File System trigger in iPaaS, it is reliant on the host system 
being able to run FileSystemWatcher Class from the .NET libraries.  Many of the emulated 
SMB shares on appliances such as Cohesity or Linux servers do not run these libraries and
so those file spaces can not be used as triggers for iPaaS flows.
