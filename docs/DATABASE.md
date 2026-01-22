The Suite software uses a database called Firebird (3.0), apparently running it just as a seperate process.

You can find the databse (.fb30) files under `C:\Program Files\CESsomethingsomething\ifrogottobehonest`.

The larger .fb30 files will hold your users, timetables and such. The SYSTEM one will hold the queue for the upload, for example.

You can just copy the .fb30 files somewhere, install firebase server version 3.0 and use something like DBeaver to open the database.
