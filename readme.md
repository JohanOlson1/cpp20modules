# C++20 Modules
Currently very difficult to use C++20 Modules practically in a real application.

## Requirements
- Atleast cmake 3.28
- Atleast gcc-toolset-12
- cmake generator "Unix Makefiles" does not support modules, which I guess (though internet won't tell me clearly) that real Linux development with it is impossible.
- Alternative cmake generator "Ninja" requires atleast version 1.11, which is not in my OS (ubuntu 22), hence you need a really modern version of Ninja! Which you don't want to use!
- modules has yet to prove themselves in real applications!
- There is a learning curve to start using this new feature, both in cmake and C++.