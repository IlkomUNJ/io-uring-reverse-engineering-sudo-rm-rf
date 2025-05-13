# Defined in openclose.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_open | struct file, int, u32, struct filename, struct open_how, unsigned long | io_openat_force_async | io_uring/openclose.c | function parameter |
| | | __io_openat_prep | io_uring/openclose.c | initialized local variable, function parameter |
| | | io_openat_prep | io_uring/openclose.c | initialized local variable, function parameter |
| | | io_openat2_prep | io_uring/openclose.c | initialized local variable, function parameter |
| | | io_openat2 | io_uring/openclose.c | initialized local variable, function parameter |
| | | io_open_cleanup | io_uring/openclose.c | initialized local variable, function parameter |
| io_close | struct file, int, u32 | io_close_fixed | io_uring/openclose.c | initialized local variable, function parameter |
| | | io_close_prep | io_uring/openclose.c | initialized local variable, function parameter |
| | | io_close | io_uring/openclose.c | initialized local variable, function parameter |
| io_fixed_install | struct file, unsigned int | io_install_fixed_fd_prep | io_uring/openclose.c | function parameter |
| | | io_install_fixed_fd | io_uring/openclose.c | function parameter |
