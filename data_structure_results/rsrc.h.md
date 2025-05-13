# Defined in rsrc.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_rsrc_node | unsigned char, int, , u64, union, unsigned long, struct io_mapped_ubuf | __io_sync_cancel | io_uring/cancel.c | function parameter, declared local variable |
| | | io_install_fixed_file | io_uring/filetable.c | function parameter, declared local variable |
| | | io_fixed_fd_remove | io_uring/filetable.c | function parameter, declared local variable |
| | | io_slot_flags | io_uring/filetable.h | function parameter |
| | | io_slot_file | io_uring/filetable.h | function parameter |
| | | io_fixed_file_set | io_uring/filetable.h | function parameter |
| | | io_file_get_fixed | io_uring/io_uring.c | function parameter, declared local variable |
| | | io_msg_grab_file | io_uring/msg_ring.c | function parameter, declared local variable |
| | | io_rsrc_cache_init | io_uring/rsrc.c | function parameter |
| | | io_clear_table_tags | io_uring/rsrc.c | initialized local variable, function parameter |
| | | io_rsrc_data_alloc | io_uring/rsrc.c | function parameter |
| | | __io_sqe_files_update | io_uring/rsrc.c | function parameter, declared local variable |
| | | __io_sqe_buffers_update | io_uring/rsrc.c | function parameter, declared local variable |
| | | io_free_rsrc_node | io_uring/rsrc.c | function parameter |
| | | io_sqe_files_register | io_uring/rsrc.c | function parameter, declared local variable |
| | | headpage_already_acct | io_uring/rsrc.c | initialized local variable, function parameter |
| | | io_sqe_buffers_register | io_uring/rsrc.c | function parameter, declared local variable |
| | | io_buffer_register_bvec | io_uring/rsrc.c | function parameter, declared local variable |
| | | io_buffer_unregister_bvec | io_uring/rsrc.c | function parameter, declared local variable |
| | | io_import_reg_buf | io_uring/rsrc.c | function parameter, declared local variable |
| | | io_clone_buffers | io_uring/rsrc.c | function parameter |
| | | io_import_reg_vec | io_uring/rsrc.c | function parameter, declared local variable |
| | | io_put_rsrc_node | io_uring/rsrc.h | function parameter |
| | | io_reset_rsrc_node | io_uring/rsrc.h | initialized local variable, function parameter |
| | | io_req_assign_rsrc_node | io_uring/rsrc.h | function parameter |
| | | io_req_assign_buf_node | io_uring/rsrc.h | function parameter |
| | | io_splice_get_file | io_uring/splice.c | function parameter, declared local variable |
| io_mapped_ubuf | u64, unsigned int, unsigned int, unsigned int, refcount_t, unsigned long, void (*release)(void, void, bool, u8, struct bio_vec bvec[] | io_uring_show_fdinfo | io_uring/fdinfo.c | initialized local variable, function parameter |
| | | io_release_ubuf | io_uring/rsrc.c | initialized local variable, function parameter |
| | | io_free_imu | io_uring/rsrc.c | function parameter |
| | | io_buffer_unmap | io_uring/rsrc.c | function parameter |
| | | io_rsrc_cache_init | io_uring/rsrc.c | function parameter |
| | | headpage_already_acct | io_uring/rsrc.c | function parameter, declared local variable |
| | | io_buffer_account_pin | io_uring/rsrc.c | function parameter |
| | | io_sqe_buffer_register | io_uring/rsrc.c | initialized local variable, function parameter |
| | | io_buffer_register_bvec | io_uring/rsrc.c | function parameter, declared local variable |
| | | validate_fixed_range | io_uring/rsrc.c | function parameter |
| | | io_import_kbuf | io_uring/rsrc.c | function parameter |
| | | io_import_fixed | io_uring/rsrc.c | function parameter |
| | | io_vec_fill_bvec | io_uring/rsrc.c | function parameter |
| | | io_estimate_bvec_size | io_uring/rsrc.c | function parameter |
| | | io_vec_fill_kern_bvec | io_uring/rsrc.c | function parameter |
| | | iov_kern_bvec_size | io_uring/rsrc.c | function parameter |
| | | io_kern_bvec_size | io_uring/rsrc.c | function parameter |
| | | io_import_reg_vec | io_uring/rsrc.c | function parameter, declared local variable |
| io_imu_folio_data | unsigned int, unsigned int, unsigned int, unsigned int | io_region_init_ptr | io_uring/memmap.c | function parameter, declared local variable |
| | | io_coalesce_buffer | io_uring/rsrc.c | function parameter |
| | | io_check_coalesce_buffer | io_uring/rsrc.c | function parameter |
| | | io_sqe_buffer_register | io_uring/rsrc.c | function parameter, declared local variable |
