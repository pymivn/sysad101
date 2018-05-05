# Basic Linux System Administrator

## Lớp học đã ngừng hoạt động.

Học Python? đăng ký tại [pymi.vn](https://pymi.vn)

* [FaceBook Page](https://www.facebook.com/familug)
* Instructor(s): HVN at [FAMILUG.org](http://www.familug.org/)
* Course number: PyMiVN SysAd101
* Level: newbie

Khoá học sử dụng một hệ điều hành nhân Linux.
Tìm hiểu các thành phần của một hệ điều hành, cách cài đặt, cấu hình, quản trị, vận hành các dịch vụ. Các câu lệnh cần thiết, có thể chạy trên mọi hệ điều hành UNIX-like (OSX, BSD, Fedora, Kali, BackTrack, Ubuntu, Debian...).
Cài đặt các dịch vụ thiết yếu đối với một Linux Sysadmin như Web server, DB.
Cài đặt 1 webapp viết bằng Golang và một Django webapp viết bằng Python.

Khoá học OFFLINE, bằng tiếng Việt, nhưng mọi từ khoá sẽ giữ nguyên tiếng Anh.

---

## [Đăng ký ](https://goo.gl/forms/MMfY9UH5SNrt5Yy62)

Bấm vào chữ đăng ký ở trên rồi điền thông tin.

**Xem danh sách đã đăng ký [tại đây](https://docs.google.com/spreadsheets/d/e/2PACX-1vR9Uw7kMGsBE9Sjn2UJ28NSQGAdV_Mc00WA-TPBLMh9Le9f8d1-VzYQ6gMIP8f29n5ZWz48mIwyDZ0U/pubhtml?gid=1701933188&single=true)**

---

* Lớp học chỉ mở khi đã đủ > 10 học viên. Hãy đăng ký! chúng tôi sẽ liên lạc lại
khi đủ học viên.
* Nhập email vào [đây](http://invite.pymi.vn/) để nhận thư mời tham gia forum của lớp, channel `#sysad101`
* HN - tại số 19, ngõ 376, Khương Đình, Hà Nội.
* Lớp HCM dự kiến khai giảng tháng 8 2017.
* Học thứ 2,4 từ 19h->21h30.
* Học phí: 4.000.000 VND, đóng vào buổi học 2nd (bạn được học thử
  buổi đầu miễn phí).
* Giảm ngay 5% học phí (sau khi đã giảm giá - nếu có) khi học viên chia sẻ
  [bài viết này](https://www.facebook.com/familug/photos/a.362246860495308.89778.356337084419619/1337935746259743/?type=3)
  lên FaceBook timeline ở chế độ public với nội dung "Học Linux SysAdmin tại #FAMILUG"

---

## Syllabus

### Week 1

#### The OS

![Ubuntu](ubuntu.png)

- Installing OS: [Ubuntu **16.04** ](https://www.ubuntu.com/)
- Version scheme: lsb_release
- Release cycle
- Debian distro, other distros
- OS components
- The Linux kernel: uname

#### Command line basic
- file/directory: cd, pwd, mkdir, ls, cp, mv, rm ...
- cat, less, tail, head
- system information: df, du, file, free, dmesg
- nano, vi

#### Processes
- Process, memory,

---

### Week 2

#### Installing package and package management
- `apt` basic
- `dpkg`
- install/upgrade/dist-upgrade/remove/purge

#### Basic scripting - bash
Write and run simple script

- `-ex`
- run it
- header shebang
- `if, [`
- VARIABLE

#### SSH
- ssh server, ssh client
- SSH tunnel
- tmux/screen

### Filesystem, partitions, swap
- FHS
- /proc
- /dev

#### User, group, permission
- Chmod
- User and group
- passwd

#### More commands
- cut
- tr
- uniq
- sort

#### Networking
- TCP/UDP
- IP
- ARP
- routing table
- network interface

---

### Week 3

#### Cron
- crontab
- `run-parts`
- daily, hourly, weekly

#### Installing popular services
- `apt-cache`
- HTTP: NGINX
- DNS: bind
- SMTP server: postfix
- DB: postgresql
- Cron
- openssh-server
- Docker
- PPA
- NoSQL: memcached, redis, elasticsearch
- Influxdb server & Grafana

#### Init system

#### Logging
- Reading syslog and service logs

#### sudo

#### Scripting, bash, sh, python

- Write script to do common tasks and process log

---

### Week 4

#### Deploy Mattermost
- Mattermost
- Database: postgresql
- HTTP server

- SSL/TLS HTTPS

#### Deploy Django app
- Pip, virtualenv
- App server: gunicorn

---

### Week 5

#### Monitoring
- Shinken/nagios
- Graphite/diamond

#### SCP backup
- SCP
- Rsync

## Readings
- [Debian Handbook](https://debian-handbook.info)
- [Ubuntu Xenial Manpage](http://manpages.ubuntu.com/manpages/xenial/en/)
- [FAMILUG.ORG](http://www.familug.org/)

## FAQs

### Giảng viên là ai?
- Giảng viên lớp học [Python] đã dạy hơn 10 khoá học trên cả nước.
- Linux User từ Ubuntu 8.04 (2008).
- Contributor của các phần mềm dùng trong SysAdmin như SaltStack, Diamond, xem
  chi tiết tại: [GitHub](https://github.com/hvnsweeting/)
- [Người tổ chức SaltStack meetup ở Việt Nam](https://www.meetup.com/VietNam-SaltStack-Meetup/).
- Xem [Resume](https://docs.google.com/document/d/1UOI6py9e83XGes32Vikq6_ZzOJMOqWB0u0zvkI3fab8/pub)

### Học xong còn khoá nâng cao hơn không?
- Có, chúng tôi đang phát triển khoá học [DevOps]. Một SysAdmin cũng có thể
  nâng cao tay nghề bằng việc học lập trình [Python].

### Tôi có cần biết gì trước khi học không?
- Cài hệ điều hành Ubuntu 16.04 lên laptop của bạn hoặc [máy ảo](
  https://medium.com/@doanhtu/h%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-c%C3%A0i-ubuntu-server-tr%C3%AAn-vmware-player-726f1f08ad35).
  Khuyến khích cài và chuyển sang dùng hẳn máy thật Ubuntu 16.04.
- Tâp bật tắt máy.
- Luyện gõ càng nhanh càng tốt.
- Biết tra từ điển [Anh-Việt](https://vdict.com/) hay dùng [Google Translate](https://translate.google.com/).

### Tài trợ
- Tài trợ cloud: [![https://greencloudvps.com/](greencloud.png)](https://greencloudvps.com/)

[DevOps]: devops/
[Python]: https://pymi.vn
