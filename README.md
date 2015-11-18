# EF7-USE
Exploring what Entity Framework 7 can do for USE

## Installing .NET tools on Linux
http://docs.asp.net/en/latest/getting-started/installing-on-linux.html

### Downgrade libicu:
```
wget http://security.ubuntu.com/ubuntu/pool/main/i/icu/libicu52_52.1-8ubuntu0.2_amd64.deb
sudo dpkg -i libicu52_52.1-8ubuntu0.2_amd64.deb
```

### 'extra dependencies?'

some of these may be optional... this is just the order I did things in to get my program to run

```
sudo apt-get install asp.net-examples

mozroots --import --sync

http://www.mono-project.com/docs/getting-started/install/linux/
sudo apt-get install mono-devel mono-complete referenceassemblies-pcl
dnvm install -r coreclr latest -u
```

## Running the program

```
dnu restore # update dependencies
dnx run # runs the program
```
