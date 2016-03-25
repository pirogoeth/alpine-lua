alpine-lua
==========

alpine-lua is a minimal Docker image built to be as lightweight and
secure as possible.

The only real components provided are a Lua version and a build of Luarocks,
built from the Git master branch.


packages
========

APK:
 - lua5.x          (depends on LUA_VERSION env)
 - lua5.x-dev      (depends on LUA_VERSION env)
 - build-base      (depended on by luarocks, C-based rocks)
 - git             (depended on by luarocks)
 - bash            (depended on by ci)
 - unzip           (depended on by luarocks/luazip)

Git:
 - https://github.com/keplerproject/luarocks.git


versions
========

 - lua5.1
 - lua5.2
