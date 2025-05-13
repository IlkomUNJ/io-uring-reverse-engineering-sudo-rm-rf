# Defined in eventfd.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_ev_fd | struct eventfd_ctx, unsigned int, unsigned, refcount_t, atomic_t, struct rcu_head | io_eventfd_free | io_uring/eventfd.c | initialized local variable, function parameter |
| | | io_eventfd_put | io_uring/eventfd.c | function parameter |
| | | io_eventfd_do_signal | io_uring/eventfd.c | initialized local variable, function parameter |
| | | io_eventfd_release | io_uring/eventfd.c | function parameter |
| | | __io_eventfd_signal | io_uring/eventfd.c | function parameter |
| | | io_eventfd_trigger | io_uring/eventfd.c | function parameter |
| | | io_eventfd_signal | io_uring/eventfd.c | declared local variable, function parameter |
| | | io_eventfd_flush_signal | io_uring/eventfd.c | declared local variable, function parameter |
| | | io_eventfd_register | io_uring/eventfd.c | function parameter |
| | | io_eventfd_unregister | io_uring/eventfd.c | function parameter |
