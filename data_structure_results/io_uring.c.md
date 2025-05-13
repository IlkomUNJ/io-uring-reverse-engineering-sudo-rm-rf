# Defined in io_uring.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_defer_entry | struct list_head, struct io_kiocb, u32 | io_queue_deferred | io_uring/io_uring.c | function parameter |
| | | io_drain_req | io_uring/io_uring.c | declared local variable, function parameter |
| | | io_cancel_defer_files | io_uring/io_uring.c | function parameter |
| ext_arg | size_t, struct timespec64, const sigset_t __user, ktime_t, bool, bool | __io_cqring_wait_schedule | io_uring/io_uring.c | return value |
| | | io_cqring_wait_schedule | io_uring/io_uring.c | function parameter |
| | | io_cqring_wait | io_uring/io_uring.c | function parameter |
| | | io_get_ext_arg | io_uring/io_uring.c | initialized local variable |
| | | SYSCALL_DEFINE6 | io_uring/io_uring.c | function parameter |
| io_tctx_exit | struct callback_head, struct completion, struct io_ring_ctx | io_tctx_exit_cb | io_uring/io_uring.c | function parameter |
| | | io_ring_exit_work | io_uring/io_uring.c | declared local variable, function parameter |
| io_task_cancel | struct io_uring_task, bool | io_cancel_task_cb | io_uring/io_uring.c | initialized local variable, function parameter |
| | | io_uring_try_cancel_requests | io_uring/io_uring.c | initialized local variable, function parameter |
