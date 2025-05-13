# Defined in io-wq.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_wq_hash | refcount_t, unsigned long, struct wait_queue_head | io_wq_put_hash | io_uring/io-wq.h | function parameter |
| | | io_init_wq_offload | io_uring/tctx.c | declared local variable, function parameter |
| io_wq_data | struct io_wq_hash, struct task_struct, io_wq_work_fn, free_work_fn | io_wq_create | io_uring/io-wq.c | function parameter |
| | | io_init_wq_offload | io_uring/tctx.c | declared local variable, function parameter |
