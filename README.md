# Lua 5.1 UTF-8
Requires a global "bit" library, such as LuaJIT 2.0.3's. This is only tested under LuaJIT 2.0.3.

All functionality is documented under Lua 5.3's documentation for the "utf8" library with the exception of utf8.force, which replaces all invalid UTF-8 sequences with the Unicode "Replacement Character" (U+FFFD).

http://www.lua.org/manual/5.3/manual.html
