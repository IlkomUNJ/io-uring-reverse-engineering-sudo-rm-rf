# epoll.c

| Library | Function utilized | Time Used |
| - | - | - |
| include/linux/io_uring_types.h | io_kiocb_to_cmd | 4 |
| tools/sched_ext/include/scx/common.bpf.h | READ_ONCE | 4 |
| include/linux/eventpoll.h | ep_op_has_event | 1 |
| include/linux/kernel.h | u64_to_user_ptr | 2 |
| include/linux/uaccess.h | copy_from_user | 1 |
| fs/eventpoll.c | do_epoll_ctl | 1 |
| io_uring/io_uring.h | req_set_fail | 2 |
| io_uring/io_uring.h | io_req_set_res | 2 |
| fs/eventpoll.c | epoll_sendevents | 1 |
