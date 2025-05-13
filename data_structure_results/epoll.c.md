# Defined in epoll.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_epoll | struct file, int, int, int, struct epoll_event | io_epoll_ctl_prep | io_uring/epoll.c | function parameter, initialized local variable |
| | | io_epoll_ctl | io_uring/epoll.c | function parameter, initialized local variable |
| io_epoll_wait | struct file, int, struct epoll_event __user | io_epoll_wait_prep | io_uring/epoll.c | function parameter, initialized local variable |
| | | io_epoll_wait | io_uring/epoll.c | function parameter, initialized local variable |
