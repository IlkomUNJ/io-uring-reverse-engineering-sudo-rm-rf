# Defined in rw.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_meta_state | u32, struct iov_iter_state 
| io_async_rw | struct iou_vec, size_t, , , struct iov_iter, struct iov_iter_state, struct iovec, union, struct wait_page_queue, struct, struct uio_meta, struct io_meta_state | io_ring_ctx_alloc | io_uring/io_uring.c | function parameter |
| | | io_import_vec | io_uring/rw.c | function parameter |
| | | __io_import_rw_buffer | io_uring/rw.c | function parameter |
| | | io_import_rw_buffer | io_uring/rw.c | function parameter |
| | | io_rw_recycle | io_uring/rw.c | initialized local variable, function parameter |
| | | io_rw_alloc_async | io_uring/rw.c | declared local variable, function parameter |
| | | io_meta_save_state | io_uring/rw.c | function parameter |
| | | io_meta_restore | io_uring/rw.c | function parameter |
| | | io_prep_rw_pi | io_uring/rw.c | declared local variable, function parameter |
| | | io_init_rw_fixed | io_uring/rw.c | initialized local variable, function parameter |
| | | io_rw_import_reg_vec | io_uring/rw.c | function parameter |
| | | io_rw_prep_reg_vec | io_uring/rw.c | initialized local variable, function parameter |
| | | io_rw_should_reissue | io_uring/rw.c | initialized local variable, function parameter |
| | | io_fixup_rw_res | io_uring/rw.c | initialized local variable, function parameter |
| | | io_rw_should_retry | io_uring/rw.c | initialized local variable, function parameter |
| | | io_rw_init_file | io_uring/rw.c | initialized local variable, function parameter |
| | | __io_read | io_uring/rw.c | initialized local variable, function parameter |
| | | io_write | io_uring/rw.c | initialized local variable, function parameter |
| | | io_rw_cache_free | io_uring/rw.c | initialized local variable, function parameter |
