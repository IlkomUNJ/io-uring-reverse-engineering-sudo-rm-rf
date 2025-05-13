# Defined in cancel.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_cancel_data | struct io_ring_ctx, union, u64, struct file | io_cancel_req_match | io_uring/cancel.c | function parameter |
| | | io_cancel_cb | io_uring/cancel.c | function parameter, initialized local variable |
| | | io_async_cancel_one | io_uring/cancel.c | function parameter |
| | | io_try_cancel | io_uring/cancel.c | function parameter |
| | | __io_async_cancel | io_uring/cancel.c | function parameter |
| | | io_async_cancel | io_uring/cancel.c | function parameter, initialized local variable |
| | | __io_sync_cancel | io_uring/cancel.c | function parameter |
| | | io_sync_cancel | io_uring/cancel.c | function parameter, initialized local variable |
| | | io_cancel_remove | io_uring/cancel.c | function parameter |
| | | bool | io_uring/cancel.h | function parameter |
| | | io_futex_cancel | io_uring/futex.h | function parameter |
| | | io_poll_find | io_uring/poll.c | function parameter |
| | | io_poll_file_find | io_uring/poll.c | function parameter |
| | | __io_poll_cancel | io_uring/poll.c | function parameter |
| | | io_poll_cancel | io_uring/poll.c | function parameter |
| | | io_poll_remove | io_uring/poll.c | function parameter, initialized local variable |
| | | io_timeout_extract | io_uring/timeout.c | function parameter |
| | | io_timeout_cancel | io_uring/timeout.c | function parameter |
| | | io_req_task_link_timeout | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_timeout_update | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_timeout_remove | io_uring/timeout.c | function parameter, initialized local variable |
| | | io_waitid_cancel | io_uring/waitid.c | function parameter |
