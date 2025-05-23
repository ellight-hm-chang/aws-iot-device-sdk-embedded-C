
git clone https://github.com/microsoft/vcpkg.git
ex: c:/vcpkg

cd vcpkg

./bootstrap-vcpkg.bat

./vcpkg.exe integrate install

./vcpkg.exe search pthread

./vcpkg install pthreads:x64-windows-static
