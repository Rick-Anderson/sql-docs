---
title: "getInt Method (int)"
description: "getInt Method (int)"
author: David-Engel
ms.author: davidengel
ms.date: "01/19/2017"
ms.service: sql
ms.subservice: connectivity
ms.topic: reference
apilocation: "sqljdbc.jar"
apiname: "SQLServerCallableStatement.getInt (int)"
apitype: "Assembly"
---
# getInt Method (int)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Retrieves the value of the designated parameter as an **int** in the Java programming language given the parameter index.  
  
## Syntax  
  
```  
  
public int getInt(int index)  
```  
  
#### Parameters  
 *index*  
  
 An **int** that indicates the parameter index.  
  
## Return Value  
 An **int** value.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This getInt method is specified by the getInt method in the java.sql.CallableStatement interface.  
  
 This method is supported only on [!INCLUDE[ssNoVersion](../../../includes/ssnoversion-md.md)] data types that can safely return an integer value such as int, smallint, tinyint, and bit. Using this method on any other data types will cause an exception to be thrown.  
  
## See Also  
 [getInt Method &#40;SQLServerCallableStatement&#41;](../../../connect/jdbc/reference/getint-method-sqlservercallablestatement.md)   
 [SQLServerCallableStatement Members](../../../connect/jdbc/reference/sqlservercallablestatement-members.md)   
 [SQLServerCallableStatement Class](../../../connect/jdbc/reference/sqlservercallablestatement-class.md)  
  
  
