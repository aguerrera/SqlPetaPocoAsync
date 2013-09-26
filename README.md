SqlPetaPocoAsync
================

an async, SqlServer only modifiication of the toptensoftware/PetaPoco ORM


This project is a modification of the single file PetaPoco.cs. All references to other
databases have been removed.

This is SqlServer specific, and all the calls are asynchronous.  You must use
async/away for all the data access methods.

This is all largely untested, and is the result of some heavy copying and pasting.
YMMV, caveat emptor, use at your own risk.

I realize the original project says to not use the single file, but I found it easier 
to work with.

The original License applies to this modification, and I make no claims over it.

- andy guerrera |  @aguerrera | github.com/aguerrera

