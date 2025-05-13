# Defined in sqpoll.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_sq_data | refcount_t, atomic_t, struct mutex, , struct list_head, , struct task_struct, struct wait_queue_head, , unsigned, int, pid_t, pid_t, , u64, unsigned long, struct completion | io_uring_show_fdinfo | io_uring/fdinfo.c | initialized local variable, function parameter |
| | | io_ring_exit_work | io_uring/io_uring.c | initialized local variable, function parameter |
| | | io_uring_cancel_generic | io_uring/io_uring.c | function parameter |
| | | io_register_iowq_max_workers | io_uring/register.c | initialized local variable, function parameter |
| | | io_sq_thread_unpark | io_uring/sqpoll.c | function parameter |
| | | io_sq_thread_park | io_uring/sqpoll.c | function parameter |
| | | io_sq_thread_stop | io_uring/sqpoll.c | function parameter |
| | | io_put_sq_data | io_uring/sqpoll.c | function parameter |
| | | io_sqd_update_thread_idle | io_uring/sqpoll.c | function parameter |
| | | io_sq_thread_finish | io_uring/sqpoll.c | initialized local variable, function parameter |
| | | io_sqd_events_pending | io_uring/sqpoll.c | function parameter |
| | | io_sqd_handle_event | io_uring/sqpoll.c | function parameter |
| | | io_sq_update_worktime | io_uring/sqpoll.c | function parameter |
| | | io_sq_thread | io_uring/sqpoll.c | initialized local variable, function parameter |
| | | io_sq_offload_create | io_uring/sqpoll.c | function parameter, declared local variable |
| | | io_sqpoll_wq_cpu_affinity | io_uring/sqpoll.c | initialized local variable, function parameter |
