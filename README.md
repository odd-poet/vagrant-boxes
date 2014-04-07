

# vagrant boxes


## hbase/

### hbase-0.94.box

#### 설치 정보
* OS: centos 6.3 x86_64
* Java: JDK6
* Package: CDH4
* hbase + zookeeper

#### 주의사항
* 호스트OS의 /etc/hosts에 아래 내용 추가해야 함
```
192.168.33.10   hbase.vagrant.box
```
* `hbase.vagrant.box`라는 이름으로 hbase/zookeeper에 접근할 것
* vagrant network은 *host-only* network
* 방화벽(iptables, ip6tables) 서비스는 꺼져있음.
