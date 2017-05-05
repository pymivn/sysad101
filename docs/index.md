# Basic Linux System Administrator

* [FaceBook Page](https://www.facebook.com/familug)
* Instructor(s): hvn@familug.org - tác giả blog http://www.familug.org/, https://github.com/hvnsweeting/, [người tổ chức SaltStack meetup ở Việt Nam](https://www.meetup.com/VietNam-SaltStack-Meetup/).
* Course number: PyMiVN SysAd101
* Level: newbie

Khoá học sử dụng một hệ điều hành nhân Linux.
Tìm hiểu các thành phần của một hệ điều hành, cách cài đặt, cấu hình, quản trị, vận hành các dịch vụ. Các câu lệnh cần thiết, có thể chạy trên mọi hệ điều hành UNIX-like (OSX, BSD, Fedora, Kali, BackTrack, Ubuntu, Debian...).
Cài đặt các dịch vụ thiết yếu đối với một Linux Sysadmin như Web server, DB.
Cài đặt 1 webapp viết bằng Golang và một Django webapp viết bằng Python.

Khoá học OFFLINE, bằng tiếng Việt, nhưng mọi từ khoá sẽ giữ nguyên tiếng Anh.

---

[Đăng ký](https://goo.gl/forms/MMfY9UH5SNrt5Yy62)

---

* Lớp HN dự kiến khai giảng 15/05/2017 tại số 19, ngõ 376, Khương Đình, Hà Nội.
* Lớp HCM dự kiến khai giảng tháng 8 2017.
* Học thứ 2,4 từ 19h->21h30.
* Học phí: 4.000.000 VND, đóng vào buổi học 2nd (bạn được học thử
  buổi đầu miễn phí).

---

## Syllabus

### Week 1

#### The OS
- Installing OS: Ubuntu
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

#### Installing package and package management
- `apt` basic
- `dpkg`
- install/upgrade/dist-upgrade/remove/purge

#### SSH
- ssh server, ssh client
- SSH tunnel
- tmux/screen

#### Processes
- Process, memory, filesystem

---

### Week 2

#### Filesystem, partitions, swap
- FHS
- /proc
- /dev

#### User, group, permission
- Chmod
- User and group
- passwd

#### Networking
- TCP/UDP
- IP
- ARP
- routing table
- network interface

---

### Week 3

#### Scripting, bash, sh, python

#### Cron

#### Init system

#### Logging
- Reading syslog and service logs

---

### Week 4

#### Deploy Mattermost
- Database: postgresql
- HTTP server
- Mattermost
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

## Readings
- [Debian Handbook](https://debian-handbook.info)
- [Ubuntu Xenial Manpage](http://manpages.ubuntu.com/manpages/xenial/en/)
- [FAMILUG.ORG](http://www.familug.org/)

## FAQs
### Học xong còn khoá nâng cao hơn không?
- Có, chúng tôi đang phát triển khoá học [DevOps]. Một SysAdmin cũng có thể
  nâng cao tay nghề bằng việc học lập trình [Python].

### Tôi có cần biết gì trước khi học không?
- Cài hệ điều hành Ubuntu 16.04 lên laptop của bạn.
- Tâp bật tắt máy.
- Luyện gõ càng nhanh càng tốt.
- Biết tra từ điển Anh-Việt hay dùng Google Translate.

[DevOps]: devops/
[Python]: https://pymi.vn
