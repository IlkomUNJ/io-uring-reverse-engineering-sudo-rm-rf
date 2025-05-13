# Defined in io_uring.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_wait_queue | struct wait_queue_entry, struct io_ring_ctx, unsigned, unsigned, unsigned, int, ktime_t, ktime_t, struct hrtimer, , #ifdef, ktime_t, bool,  | io_wake_function | io_uring/io_uring.c | function parameter, initialized local variable |
| | | io_cqring_timer_wakeup | io_uring/io_uring.c | function parameter, initialized local variable |
| | | io_cqring_min_timer_wakeup | io_uring/io_uring.c | function parameter, initialized local variable |
| | | io_cqring_schedule_timeout | io_uring/io_uring.c | function parameter |
| | | __io_cqring_wait_schedule | io_uring/io_uring.c | function parameter |
| | | io_cqring_wait_schedule | io_uring/io_uring.c | function parameter |
| | | io_cqring_wait | io_uring/io_uring.c | function parameter, declared local variable |
| | | io_should_wake | io_uring/io_uring.h | function parameter |
| | | io_napi_busy_loop_should_end | io_uring/napi.c | function parameter, initialized local variable |
| | | io_napi_blocking_busy_loop | io_uring/napi.c | function parameter |
| | | __io_napi_busy_loop | io_uring/napi.c | function parameter |
| | | io_napi_busy_loop | io_uring/napi.h | function parameter |
