# MongoDB_MonitoramentoSites
Worker Services C# Project


** run build
dotnet build

** Install the worker service as Service.  Remember to run your command line as Administrator.
sc create <ServiceName> binPath=<paste your path to the .exe file>\<fileApplication.exe> start=auto

** Remember to paste your path to the .exe file. 

** Now check your Services. 
	To open services click on Windows key, then start writing Services

** Check that your service is installed.

** You can use sc utility also to Stop, Start and Delete services.

sc start DemoWorkerService
sc stop DemoWorkerService
sc delete DemoWorkerService

** Event Viewer
Now Start your Service and check Event Viewer

To open Event Viewer click on Windows key and start writing Event Viewer
	Windows Logs Group
		Application Viewer		

You must to install a mongoDB instance or change the connection string  to another Mongo instance
