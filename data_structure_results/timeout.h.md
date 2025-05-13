# Defined in timeout.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_timeout_data | struct io_kiocb, struct hrtimer, struct timespec64, enum hrtimer_mode, u32 | io_is_timeout_noseq | io_uring/timeout.c | initialized local variable, function parameter |
| | | io_timeout_finish | io_uring/timeout.c | function parameter |
| | | io_timeout_complete | io_uring/timeout.c | initialized local variable, function parameter |
| | | io_kill_timeout | io_uring/timeout.c | initialized local variable, function parameter |
| | | __io_disarm_linked_timeout | io_uring/timeout.c | initialized local variable, function parameter |
| | | io_timeout_fn | io_uring/timeout.c | function parameter |
| | | io_timeout_extract | io_uring/timeout.c | declared local variable, function parameter |
| | | io_link_timeout_fn | io_uring/timeout.c | function parameter |
| | | io_timeout_get_clock | io_uring/timeout.c | function parameter |
| | | io_linked_timeout_update | io_uring/timeout.c | declared local variable, function parameter |
| | | io_timeout_update | io_uring/timeout.c | declared local variable, function parameter |
| | | __io_timeout_prep | io_uring/timeout.c | declared local variable, function parameter |
| | | io_timeout | io_uring/timeout.c | initialized local variable, function parameter |
| | | io_queue_linked_timeout | io_uring/timeout.c | initialized local variable, function parameter |
