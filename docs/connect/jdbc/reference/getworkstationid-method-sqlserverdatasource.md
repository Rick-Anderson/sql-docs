---
title: "getWorkstationID Method (SQLServerDataSource)"
description: "getWorkstationID Method (SQLServerDataSource)"
author: David-Engel
ms.author: davidengel
ms.date: "01/19/2017"
ms.service: sql
ms.subservice: connectivity
ms.topic: reference
apilocation: "sqljdbc.jar"
apiname: "SQLServerDataSource.getWorkstationID"
apitype: "Assembly"
---
# getWorkstationID Method (SQLServerDataSource)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Returns the name of the client computer name that is used to connect to the data source.  
  
## Syntax  
  
```  
  
public java.lang.String getWorkstationID()  
```  
  
## Return Value  
 A **String** that contains the client computer name.  
  
## Remarks  
 The workstationID is the name of the client computer or workstation. If the workstationID property is not set, the default value is constructed by calling InetAddress.getLocalHost().getHostName() method. If getHostName returns a blank value, the getHostAddress().toString() method is called.  
  
## See Also  
 [SQLServerDataSource Members](../../../connect/jdbc/reference/sqlserverdatasource-members.md)   
 [SQLServerDataSource Class](../../../connect/jdbc/reference/sqlserverdatasource-class.md)  
  
  
