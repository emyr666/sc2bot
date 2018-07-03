# sc2bot
Basic sc2 scripted bot based on sentdex youtube channel. Uses google protobuf and websockets from boost beast.

Requirements
------------
* boost (www.boost.org) >= 1.67 (uses asio, beast)
* Google protobuf (https://github.com/google/protobuf) >= 3.6.0.1
* Blizzard sc2client-proto (https://github.com/Blizzard/s2client-proto) >= 1.2.0

Generating sc2api source files
------------------------------
You can use the protoc command from google's protobuf project against the .proto definitions from the sc2api specification. This gives you sc2api.pb.h and sc2api.pb.cc.
These files are in the src directory.
