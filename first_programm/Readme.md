## первая программа для взаимодействия с сокетами операционной системы
находит ip адресс по hostname
```bash
sib_coder@DESKTOP-RSVCLCB:/mnt/c/Users/sib-coder/CLionProjects/untitled$ gcc main.c -o main
sib_coder@DESKTOP-RSVCLCB:/mnt/c/Users/sib-coder/CLionProjects/untitled$ ls
CMakeLists.txt  cmake-build-debug  main  main.c
sib_coder@DESKTOP-RSVCLCB:/mnt/c/Users/sib-coder/CLionProjects/untitled$ ./main
usage: showip hostname
sib_coder@DESKTOP-RSVCLCB:/mnt/c/Users/sib-coder/CLionProjects/untitled$ ./main www.example.net
IP addresses for www.example.net:

  IPv4: 93.184.216.34
  IPv6: 2606:2800:220:1:248:1893:25c8:1946
sib_coder@DESKTOP-RSVCLCB:/mnt/c/Users/sib-coder/CLionProjects/untitled$

```