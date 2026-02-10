# Dockerfile
From ubuntu:22.04
HR-friendly# Bank SQLite – C++ (Docker & Tests)

Clean C++ demo project with:
- SQLite3
- Prepared statements
- CMake
- Unit tests
- Docker support

## Local Build
```bash
sudo apt install sqlite3 libsqlite3-dev
mkdir build && cd build
cmake ..
make
ctest
./bank_sqlite
This project is intended as a small but realistic backend demo
for junior / trainee / C++ developer positions.
