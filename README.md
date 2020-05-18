# ghidra-hidport

I was looking around for WDK support, and found https://github.com/NationalSecurityAgency/ghidra/issues/184 which talks about, but is currently not resolved.  
This https://github.com/0x6d696368/ghidra-data/tree/master/typeinfo was linked, which provided a lot of the missing structures and function definitions, but it didn't include hidport structures!  
  
So I manually made the structures for hidport, and so now the driver can properly call `HidRegisterMinidriver` and use the variety of structures.
