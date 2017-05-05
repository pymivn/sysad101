# Basic Linux System Administrator

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

## [Đăng ký](https://goo.gl/forms/MMfY9UH5SNrt5Yy62)

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

[DevOps]: devops/
[Python]: https://pymi.vn
