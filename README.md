#Mathematica XML-RPC

A normal request: `XMLRPCCall[url, function, args...]`

Multicall: `XMLRPCCall[url, {{ f1, ... }, { f2, ...}, ... }]`

Structs are expressed as a list of rules

Base64 is treated as a string.
