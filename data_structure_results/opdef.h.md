# Defined in opdef.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_issue_def | unsigned needs_file, unsigned plug, unsigned ioprio, unsigned iopoll, unsigned buffer_select, unsigned hash_reg_file, unsigned unbound_nonreg_file, unsigned pollin, unsigned pollout, unsigned poll_exclusive, unsigned audit_skip, unsigned iopoll_queue, unsigned vectored, unsigned short, int (*issue)(struct io_kiocb *, unsigned int), int (*prep)(struct io_kiocb *, const struct io_uring_sqe *) | io_prep_async_work | io_uring/io_uring.c | function parameter, initialized local variable |
| | | io_assign_file | io_uring/io_uring.c | function parameter |
| | | __io_issue_sqe | io_uring/io_uring.c | function parameter |
| | | io_issue_sqe | io_uring/io_uring.c | function parameter, initialized local variable |
| | | io_wq_submit_work | io_uring/io_uring.c | function parameter, initialized local variable |
| | | io_init_req | io_uring/io_uring.c | declared local variable, function parameter |
| | | io_uring_alloc_async_data | io_uring/io_uring.h | function parameter, initialized local variable |
| | | io_arm_poll_handler | io_uring/poll.c | function parameter, initialized local variable |
| | | __io_import_rw_buffer | io_uring/rw.c | function parameter, initialized local variable |
| io_cold_def | const char, , void (*cleanup)(struct io_kiocb, void (*fail)(struct io_kiocb | io_clean_op | io_uring/io_uring.c | function parameter, initialized local variable |
| | | io_req_defer_failed | io_uring/io_uring.c | function parameter, initialized local variable |
