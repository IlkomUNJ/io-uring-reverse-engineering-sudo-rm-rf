# Defined in waitid.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_waitid | struct file, int, pid_t, int, atomic_t, struct wait_queue_head, struct siginfo __user, struct waitid_info | io_waitid_compat_copy_si | io_uring/waitid.c | function parameter |
| | | io_waitid_copy_si | io_uring/waitid.c | function parameter, initialized local variable |
| | | io_waitid_complete | io_uring/waitid.c | function parameter, initialized local variable |
| | | __io_waitid_cancel | io_uring/waitid.c | function parameter, initialized local variable |
| | | io_waitid_drop_issue_ref | io_uring/waitid.c | function parameter, initialized local variable |
| | | io_waitid_cb | io_uring/waitid.c | function parameter, initialized local variable |
| | | io_waitid_wait | io_uring/waitid.c | function parameter, initialized local variable |
| | | io_waitid_prep | io_uring/waitid.c | function parameter, initialized local variable |
| | | io_waitid | io_uring/waitid.c | function parameter, initialized local variable |
