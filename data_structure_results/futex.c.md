# Defined in futex.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_futex | struct file, union, u32 __user, struct futex_waitv, __user | io_futexv_complete | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futexv_claim | io_uring/futex.c | function parameter |
| | | __io_futex_cancel | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futex_prep | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futex_wakev_fn | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futexv_prep | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futexv_wait | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futex_wait | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futex_wake | io_uring/futex.c | function parameter, initialized local variable |
| io_futex_data | struct futex_q, struct io_kiocb | io_futex_cache_init | io_uring/futex.c | function parameter |
| | | __io_futex_cancel | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futex_wake_fn | io_uring/futex.c | function parameter, initialized local variable |
| | | io_futex_wait | io_uring/futex.c | function parameter, initialized local variable |
