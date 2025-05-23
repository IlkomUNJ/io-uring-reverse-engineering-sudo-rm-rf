# kbuf.c

| Library | Function utilized | Time Used |
| - | - | - |
| io_uring/kbuf.c | io_ring_head_to_buf | 4 |
| include/linux/minmax.h | min_t | 3 |
| io_uring/kbuf.c | io_kbuf_inc_commit | 1 |
| include/linux/lockdep.h | lockdep_assert_held | 6 |
| lib/xarray.c | xa_load | 2 |
| include/linux/cleanup.h | guard | 1 |
| include/linux/xarray.h | xa_err | 1 |
| tools/include/asm/bug.h | WARN_ON_ONCE | 2 |
| mm/slub.c | kfree | 6 |
| io_uring/io_uring.h | io_ring_submit_lock | 5 |
| io_uring/kbuf.c | io_buffer_get_list | 9 |
| include/linux/list.h | list_add | 1 |
| io_uring/io_uring.h | io_ring_submit_unlock | 5 |
| include/linux/list.h | list_empty | 4 |
| include/linux/list.h | list_first_entry | 2 |
| include/linux/list.h | list_del | 2 |
| include/linux/kernel.h | u64_to_user_ptr | 3 |
| io_uring/kbuf.c | io_provided_buffer_select | 2 |
| tools/arch/sparc/include/asm/barrier_64.h | smp_load_acquire | 2 |
| io_uring/io_uring.h | io_file_can_poll | 1 |
| io_uring/kbuf.c | io_kbuf_commit | 3 |
| io_uring/kbuf.c | io_ring_buffer_select | 1 |
| tools/include/linux/compiler.h | READ_ONCE | 8 |
| include/linux/minmax.h | min_not_zero | 1 |
| include/linux/slab.h | kmalloc_array | 1 |
| io_uring/kbuf.c | io_ring_buffers_peek | 2 |
| io_uring/kbuf.c | io_provided_buffers_select | 2 |
| io_uring/kbuf.c | io_kbuf_drop_legacy | 1 |
| io_uring/kbuf.c | __io_put_kbuf_ring | 1 |
| io_uring/memmap.c | io_free_region | 2 |
| include/linux/list.h | INIT_LIST_HEAD | 2 |
| lib/test_maple_tree.c | cond_resched | 2 |
| io_uring/kbuf.c | __io_remove_buffers | 2 |
| include/linux/cleanup.h | scoped_guard | 3 |
| lib/xarray.c | xa_find | 1 |
| lib/xarray.c | xa_erase | 2 |
| io_uring/kbuf.c | io_put_bl | 3 |
| include/linux/io_uring_types.h | io_kiocb_to_cmd | 4 |
| mm/kasan/shadow.c | memset | 2 |
| io_uring/io_uring.h | req_set_fail | 2 |
| io_uring/io_uring.h | io_req_set_res | 2 |
| include/linux/overflow.h | check_mul_overflow | 1 |
| include/linux/overflow.h | check_add_overflow | 1 |
| tools/perf/util/include/asm/uaccess.h | access_ok | 1 |
| lib/decompress_unxz.c | kmalloc | 1 |
| include/linux/list.h | list_add_tail | 1 |
| include/linux/slab.h | kzalloc | 2 |
| io_uring/kbuf.c | io_buffer_add_list | 2 |
| io_uring/kbuf.c | io_add_buffers | 1 |
| include/linux/uaccess.h | copy_from_user | 3 |
| include/linux/log2.h | is_power_of_2 | 1 |
| io_uring/kbuf.c | io_destroy_bl | 1 |
| include/linux/overflow.h | flex_array_size | 1 |
| include/linux/mm.h | PAGE_ALIGN | 1 |
| io_uring/memmap.c | io_create_region_mmap_safe | 1 |
| io_uring/memmap.h | io_region_get_ptr | 1 |
| fs/orangefs/orangefs-debug.h | ARRAY_SIZE | 1 |
| include/linux/uaccess.h | copy_to_user | 1 |
