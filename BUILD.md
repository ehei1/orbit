# build

* windows only

```bash
# 0. open powershell
# 1. source clone
git clone --recurse-submodules https://github.com/ehei1/orbit.git
.\vcpkg\bootstrap-vcpkg.bat

# 2. Run and read message from it. Copy instruction
.\vcpkg\vcpkg integrate project

# 3. open Orbit.sln with Visual Studio 2019
# 4. With a project open, go to Tools->NuGet Package Manager->Package Manager Console and paste it
# 5. build it
```