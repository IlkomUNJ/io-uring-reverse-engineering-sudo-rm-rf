# Defined in uring_cmd.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_async_cmd | struct io_uring_cmd_data, struct iou_vec, struct io_uring_sqe | io_ring_ctx_alloc | io_uring/io_uring.c | function parameter |
| | | io_cmd_cache_free | io_uring/uring_cmd.c | initialized local variable, function parameter |
| | | io_req_uring_cleanup | io_uring/uring_cmd.c | initialized local variable, function parameter |
| | | io_uring_cmd_prep_setup | io_uring/uring_cmd.c | function parameter |
| | | io_uring_cmd_import_fixed_vec | io_uring/uring_cmd.c | initialized local variable, function parameter |
