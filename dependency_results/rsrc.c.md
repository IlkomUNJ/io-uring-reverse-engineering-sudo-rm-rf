# rsrc.c

| Library | Function utilized | Time Used |
| - | - | - |
| include/uapi/linux/resource.h | rlimit | 2 |
| include/linux/atomic/atomic-instrumented.h | atomic_long_read | 1 |
| include/linux/atomic/atomic-instrumented.h | atomic_long_try_cmpxchg | 1 |
| io_uring/rsrc.h | __io_unaccount_mem | 1 |
| include/linux/atomic/atomic-instrumented.h | atomic64_sub | 1 |
| io_uring/rsrc.c | __io_account_mem | 1 |
| include/linux/atomic/atomic-instrumented.h | atomic64_add | 1 |
| include/linux/overflow.h | check_add_overflow | 4 |
| mm/gup.c | unpin_user_page | 1 |
| io_uring/alloc_cache.h | io_cache_alloc | 2 |
| include/linux/slab.h | kvmalloc | 1 |
| io_uring/alloc_cache.h | io_cache_free | 3 |
| mm/slub.c | kvfree | 4 |
| include/linux/refcount.h | refcount_dec_and_test | 1 |
| io_uring/rsrc.c | io_unaccount_mem | 1 |
| net/netlink/af_netlink.h | release | 1 |
| io_uring/rsrc.c | io_free_imu | 2 |
| include/linux/overflow.h | struct_size_t | 1 |
| io_uring/alloc_cache.c | io_alloc_cache_init | 2 |
| io_uring/alloc_cache.c | io_alloc_cache_free | 2 |
| io_uring/rsrc.h | io_put_rsrc_node | 2 |
| include/linux/slab.h | kvmalloc_array | 2 |
| include/linux/kernel.h | u64_to_user_ptr | 9 |
| include/linux/uaccess.h | copy_from_user | 11 |
| io_uring/rsrc.h | io_reset_rsrc_node | 2 |
| io_uring/filetable.h | io_file_bitmap_clear | 1 |
| fs/file.c | fget | 3 |
| include/linux/io_uring.h | io_is_uring_fops | 2 |
| fs/file_table.c | fput | 6 |
| io_uring/rsrc.c | io_rsrc_node_alloc | 5 |
| io_uring/filetable.h | io_fixed_file_set | 2 |
| io_uring/filetable.h | io_file_bitmap_set | 2 |
| lib/iov_iter.c | iovec_from_user | 3 |
| fs/bcachefs/trace.h | IS_ERR | 7 |
| include/linux/err.h | PTR_ERR | 7 |
| io_uring/rsrc.c | io_buffer_validate | 2 |
| io_uring/rsrc.c | io_sqe_buffer_register | 2 |
| include/linux/nospec.h | array_index_nospec | 3 |
| include/linux/lockdep.h | lockdep_assert_held | 3 |
| io_uring/rsrc.c | __io_sqe_files_update | 1 |
| io_uring/rsrc.c | __io_sqe_buffers_update | 1 |
| mm/kasan/shadow.c | memset | 3 |
| io_uring/rsrc.c | __io_register_rsrc_update | 3 |
| io_uring/rsrc.c | io_sqe_files_register | 1 |
| io_uring/rsrc.c | io_sqe_buffers_register | 1 |
| include/linux/io_uring_types.h | io_kiocb_to_cmd | 3 |
| tools/include/linux/compiler.h | READ_ONCE | 3 |
| io_uring/filetable.c | io_fixed_fd_install | 1 |
| include/linux/uaccess.h | copy_to_user | 1 |
| io_uring/openclose.c | __io_close_fixed | 1 |
| io_uring/rsrc.c | io_files_update_with_index_alloc | 1 |
| io_uring/io_uring.h | io_ring_submit_lock | 4 |
| io_uring/io_uring.h | io_ring_submit_unlock | 4 |
| io_uring/io_uring.h | req_set_fail | 1 |
| io_uring/io_uring.h | io_req_set_res | 1 |
| io_uring/io_uring.c | io_post_aux_cqe | 1 |
| io_uring/rsrc.c | io_buffer_unmap | 2 |
| tools/include/asm/bug.h | WARN_ON_ONCE | 3 |
| io_uring/filetable.c | io_free_file_tables | 1 |
| io_uring/filetable.h | io_file_table_set_alloc_range | 2 |
| io_uring/filetable.c | io_alloc_file_tables | 1 |
| io_uring/rsrc.c | io_clear_table_tags | 2 |
| io_uring/rsrc.c | io_sqe_files_unregister | 1 |
| io_uring/rsrc.c | io_rsrc_data_free | 3 |
| include/linux/page-flags.h | PageCompound | 3 |
| include/linux/page-flags.h | compound_head | 4 |
| io_uring/rsrc.c | headpage_already_acct | 1 |
| include/linux/mm.h | page_size | 1 |
| io_uring/rsrc.c | io_account_mem | 1 |
| mm/gup.c | unpin_user_pages | 3 |
| include/linux/minmax.h | min_t | 3 |
| include/linux/page-flags.h | page_folio | 3 |
| include/linux/mm.h | folio_nr_pages | 1 |
| include/linux/mm.h | folio_shift | 1 |
| include/linux/mm.h | folio_page_idx | 2 |
| include/linux/mm.h | folio_size | 1 |
| include/linux/err.h | ERR_PTR | 2 |
| io_uring/memmap.c | io_pin_pages | 1 |
| block/blk-sysfs.c | page | 1 |
| io_uring/rsrc.c | io_check_coalesce_buffer | 1 |
| io_uring/rsrc.c | io_coalesce_buffer | 1 |
| io_uring/rsrc.c | io_alloc_imu | 2 |
| io_uring/rsrc.c | io_buffer_account_pin | 1 |
| include/linux/refcount.h | refcount_set | 2 |
| include/linux/bvec.h | bvec_set_page | 2 |
| include/linux/build_bug.h | BUILD_BUG_ON | 1 |
| io_uring/rsrc.c | io_rsrc_data_alloc | 2 |
| io_uring/rsrc.c | io_sqe_buffers_unregister | 1 |
| include/linux/io_uring_types.h | cmd_to_io_kiocb | 2 |
| include/linux/blk-mq.h | blk_rq_nr_phys_segments | 1 |
| mm/slub.c | kfree | 2 |
| include/linux/blk-mq.h | blk_rq_bytes | 1 |
| include/linux/blk-mq.h | rq_data_dir | 1 |
| include/linux/blk-mq.h | rq_for_each_bvec | 1 |
| lib/iov_iter.c | iov_iter_bvec | 4 |
| lib/iov_iter.c | iov_iter_advance | 2 |
| io_uring/rsrc.c | validate_fixed_range | 3 |
| io_uring/rsrc.c | io_import_kbuf | 1 |
| io_uring/rsrc.h | io_rsrc_node_lookup | 2 |
| io_uring/rsrc.h | io_req_assign_buf_node | 1 |
| io_uring/rsrc.c | io_find_buf_node | 2 |
| io_uring/rsrc.c | io_import_fixed | 1 |
| include/linux/minmax.h | swap | 1 |
| kernel/locking/rtmutex_api.c | mutex_lock | 1 |
| kernel/locking/mutex.c | mutex_lock_nested | 1 |
| include/linux/minmax.h | max | 1 |
| include/linux/minmax.h | min | 1 |
| include/linux/refcount.h | refcount_inc | 1 |
| lib/string.c | memchr_inv | 1 |
| io_uring/register.c | io_uring_register_get_file | 1 |
| kernel/locking/rtmutex_api.c | mutex_unlock | 2 |
| io_uring/rsrc.c | lock_two_rings | 1 |
| io_uring/rsrc.c | io_clone_buffers | 1 |
| include/linux/slab.h | kmalloc_array | 1 |
| io_uring/rsrc.c | io_vec_free | 2 |
| include/linux/bvec.h | bvec_iter_advance | 1 |
| include/linux/bvec.h | for_each_mp_bvec | 1 |
| io_uring/rsrc.c | iov_kern_bvec_size | 1 |
| io_uring/rsrc.c | io_kern_bvec_size | 1 |
| io_uring/rsrc.c | io_estimate_bvec_size | 1 |
| io_uring/rsrc.c | io_vec_realloc | 2 |
| mm/kasan/shadow.c | memcpy | 1 |
| io_uring/rsrc.c | io_vec_fill_kern_bvec | 1 |
| io_uring/rsrc.c | io_vec_fill_bvec | 1 |
| io_uring/io_uring.h | io_is_compat | 1 |
