#High-performance BitTorrent Tracker

Use the following commands to install the dependencies on Debian. The g++ version should be at least 4.7.
```
apt-get install cmake g++ libboost-dev libmysqlclient-dev make subversion zlib1g-dev
```
Use the following commands to install some of the dependencies on CentOS. The g++ version should be at least 4.7.<br/>

```
yum install boost-devel cmake gcc-c++ mysql-devel subversion
```
Enter the following commands in a terminal. Be patient while g++ is running, it'll take a few minutes.
```
git clone https://github.com/poiuty/xbt.git
cd xbt/Tracker
./make.sh
cp xbt_tracker.conf.default xbt_tracker.conf
```
