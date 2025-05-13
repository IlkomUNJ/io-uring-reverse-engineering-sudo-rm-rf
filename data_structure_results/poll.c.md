# Defined in poll.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_poll_update | struct file, u64, u64, __poll_t, bool, bool | io_poll_remove_prep | io_uring/poll.c | function parameter, initialized local variable |
| | | io_poll_remove | io_uring/poll.c | function parameter, initialized local variable |
| io_poll_table | struct poll_table_struct, struct io_kiocb, int, int, bool, __poll_t | __io_queue_proc | io_uring/poll.c | function parameter |
| | | io_poll_queue_proc | io_uring/poll.c | function parameter, initialized local variable |
| | | io_poll_can_finish_inline | io_uring/poll.c | function parameter |
| | | __io_arm_poll_handler | io_uring/poll.c | function parameter |
| | | io_async_queue_proc | io_uring/poll.c | function parameter, initialized local variable |
| | | io_arm_poll_handler | io_uring/poll.c | function parameter, declared local variable |
| | | io_poll_add | io_uring/poll.c | function parameter, declared local variable |
