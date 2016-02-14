#High-performance BitTorrent Tracker

Use the following commands to install the dependencies on Debian. The g++ version >= 4.7.
```
apt-get install cmake g++ libboost-dev libmysqlclient-dev make git zlib1g-dev
```
Use the following commands to install some of the dependencies on CentOS. The g++ version >= 4.7.<br/>

```
yum install boost-devel cmake gcc-c++ mysql-devel git
```
Enter the following commands in a terminal. Be patient while g++ is running, it'll take a few minutes.
```
git clone https://github.com/poiuty/xbt.git
cd xbt/Tracker
./make.sh
cp xbt_tracker.conf.default xbt_tracker.conf
```
