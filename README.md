How to fix self signed certificate error 

--------
Error: 
----------

x509: certificate relies on legacy Common Name field, use SANs or temporarily enable Common Name matching with GODEBUG=x509ignoreCN=0
 
------
Issue:

--------

The extension in self signed certificate request (CSR) is not getting passed to final certificate hence we are hitting the issue.
