# Defined in tctx.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_tctx_node | struct list_head, struct task_struct, struct io_ring_ctx | __io_async_cancel | io_uring/cancel.c | function parameter, declared local variable |
| | | io_ring_exit_work | io_uring/io_uring.c | function parameter |
| | | io_uring_try_cancel_iowq | io_uring/io_uring.c | function parameter, declared local variable |
| | | io_uring_cancel_generic | io_uring/io_uring.c | function parameter, declared local variable |
| | | io_register_iowq_max_workers | io_uring/register.c | function parameter, declared local variable |
| | | __io_uring_free | io_uring/tctx.c | function parameter, declared local variable |
| | | __io_uring_add_tctx_node | io_uring/tctx.c | function parameter, declared local variable |
| | | io_uring_del_tctx_node | io_uring/tctx.c | function parameter, declared local variable |
| | | io_uring_clean_tctx | io_uring/tctx.c | function parameter, declared local variable |
