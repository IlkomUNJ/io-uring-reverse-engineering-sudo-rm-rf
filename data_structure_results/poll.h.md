# Defined in poll.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_poll | struct file, struct wait_queue_head, __poll_t, int, struct wait_queue_entry | io_init_poll_iocb | io_uring/poll.c | function parameter |
| | | io_poll_remove_entry | io_uring/poll.c | function parameter |
| | | io_poll_task_func | io_uring/poll.c | function parameter |
| | | io_pollfree_wake | io_uring/poll.c | function parameter |
| | | io_poll_wake | io_uring/poll.c | initialized local variable, function parameter |
| | | io_poll_double_prepare | io_uring/poll.c | initialized local variable, function parameter |
| | | __io_queue_proc | io_uring/poll.c | initialized local variable, function parameter |
| | | io_poll_queue_proc | io_uring/poll.c | function parameter |
| | | __io_arm_poll_handler | io_uring/poll.c | function parameter |
| | | io_poll_add_prep | io_uring/poll.c | initialized local variable, function parameter |
| | | io_poll_add | io_uring/poll.c | initialized local variable, function parameter |
| | | io_poll_remove | io_uring/poll.c | initialized local variable, function parameter |
| async_poll | struct io_poll, struct io_poll | io_ring_ctx_alloc | io_uring/io_uring.c | function parameter |
| | | io_free_batch_list | io_uring/io_uring.c | initialized local variable, function parameter |
| | | io_async_queue_proc | io_uring/poll.c | initialized local variable, function parameter |
| | | io_arm_poll_handler | io_uring/poll.c | function parameter, declared local variable |
