# Defined in timeout.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_timeout | struct file, u32, u32, u32, struct list_head, struct io_kiocb, struct io_kiocb | io_is_timeout_noseq | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_timeout_finish | io_uring/timeout.c | function parameter |
| | | io_timeout_complete | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_flush_killed_timeouts | io_uring/timeout.c | function parameter |
| | | io_kill_timeout | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_flush_timeouts | io_uring/timeout.c | function parameter |
| | | __io_disarm_linked_timeout | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_timeout_fn | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_timeout_extract | io_uring/timeout.c | function parameter |
| | | io_req_task_link_timeout | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_link_timeout_fn | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_linked_timeout_update | io_uring/timeout.c | function parameter, declared local variable |
| | | io_timeout_update | io_uring/timeout.c | function parameter, initialized local variable |
| | | __io_timeout_prep | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_timeout | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_queue_linked_timeout | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_kill_timeouts | io_uring/timeout.c | function parameter |
| io_timeout_rem | struct file, u64, , struct timespec64, u32, bool | io_timeout_remove_prep | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_timeout_remove | io_uring/timeout.c | function parameter, initialized local variable |
