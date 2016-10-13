This sample code retrieves a list of clusters ordered by the number of CPUs

How To Run

In order to run this sample code you must provide three arguments:
[1] The server name or IP address
[2] The user name to log in as
[3] The password to use

You will need to get the vim25.jar library from the VMware vSphere JDK.  It is in the VMware-vSphere-SDK-5.5.0\vsphere-ws\java\JAXWS\lib directory.

You can run this sample code by downloading the zip file below, unzipping it and running a command similar to the following:
java -cp vim25.jar com.vmware.sample.GetNumOfCpuPerCluster <ip_or_name> <user> <password>
java -cp vim25.jar com.vmware.sample.GetNumOfCpuPerCluster 10.20.30.40 JoeUser JoePasswd

Output

You will see the output similar to the following when you run the sample:
Here are the list of clusters ordered by number of CPUs:
MyCluster - Num of Cpu: 8
MySecondCluster - Num of Cpu: 4
