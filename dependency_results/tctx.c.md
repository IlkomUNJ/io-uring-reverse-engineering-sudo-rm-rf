# tctx.c

| Library | Function utilized | Time Used |
| - | - | - |
| kernel/locking/mutex.c | mutex_lock | 4 |
| include/linux/slab.h | kzalloc | 2 |
| kernel/locking/mutex.c | mutex_unlock | 5 |
| include/linux/err.h | ERR_PTR | 1 |
| include/linux/refcount.h | refcount_set | 1 |
| include/linux/wait.h | init_waitqueue_head | 2 |
| include/linux/minmax.h | min | 1 |
| include/linux/cpumask.h | num_online_cpus | 1 |
| io_uring/io-wq.c | io_wq_create | 1 |
| lib/xarray.c | xa_store | 1 |
| include/linux/xarray.h | xa_empty | 1 |
| include/linux/xarray.h | xa_for_each | 2 |
| tools/include/asm/bug.h | WARN_ON_ONCE | 5 |
| include/linux/percpu_counter.h | percpu_counter_destroy | 2 |
| mm/slub.c | kfree | 5 |
| include/linux/percpu_counter.h | percpu_counter_init | 1 |
| io_uring/tctx.c | io_init_wq_offload | 1 |
| fs/xfs/xfs_trace.h | IS_ERR | 1 |
| include/linux/err.h | PTR_ERR | 1 |
| include/linux/xarray.h | xa_init | 1 |
| include/linux/atomic/atomic-instrumented.h | atomic_set | 2 |
| include/linux/llist.h | init_llist_head | 1 |
| include/linux/task_work.h | init_task_work | 1 |
| io_uring/tctx.c | io_uring_alloc_task_context | 1 |
| io_uring/io-wq.c | io_wq_max_workers | 1 |
| lib/xarray.c | xa_load | 1 |
| lib/decompress_unxz.c | kmalloc | 1 |
| include/linux/xarray.h | xa_err | 1 |
| include/linux/list.h | list_add | 1 |
| io_uring/tctx.c | __io_uring_add_tctx_node | 2 |
| lib/xarray.c | xa_erase | 1 |
| include/linux/list.h | list_del | 1 |
| io_uring/tctx.c | io_uring_del_tctx_node | 2 |
| lib/test_maple_tree.c | cond_resched | 1 |
| io_uring/io_uring.c | io_uring_try_cancel_iowq | 1 |
| io_uring/io-wq.c | io_wq_put_and_exit | 1 |
| fs/file_table.c | fput | 5 |
| include/linux/nospec.h | array_index_nospec | 2 |
| fs/file.c | fget | 1 |
| include/linux/io_uring.h | io_is_uring_fops | 1 |
| io_uring/tctx.c | io_ring_add_registered_file | 1 |
| include/linux/uaccess.h | copy_from_user | 2 |
| io_uring/tctx.c | io_ring_add_registered_fd | 1 |
| include/linux/uaccess.h | copy_to_user | 1 |
