# advise.c

| Library | Function utilized | Time Used |
| - | - | - |
| include/linux/io_uring_types.h | io_kiocb_to_cmd | 4 |
| tools/testing/selftests/bpf/bpf_atomic.h | READ_ONCE | 8 |
| tools/include/asm/bug.h | WARN_ON_ONCE | 2 |
| mm/madvise.c | do_madvise | 1 |
| io_uring/io_uring.h | io_req_set_res | 2 |
| io_uring/advise.c | io_fadvise_force_async | 2 |
| mm/fadvise.c | vfs_fadvise | 1 |
| io_uring/io_uring.h | req_set_fail | 1 |
