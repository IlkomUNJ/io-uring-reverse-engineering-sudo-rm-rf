# fdinfo.c

| Library | Function utilized | Time Used |
| - | - | - |
| include/linux/seq_file.h | seq_user_ns | 1 |
| fs/seq_file.c | seq_printf | 32 |
| fs/seq_file.c | seq_put_decimal_ull | 9 |
| kernel/user_namespace.c | from_kuid_munged | 4 |
| kernel/user_namespace.c | from_kgid_munged | 5 |
| include/linux/seq_file.h | seq_puts | 9 |
| fs/seq_file.c | seq_put_hex_ll | 1 |
| fs/seq_file.c | seq_putc | 1 |
| tools/testing/selftests/bpf/bpf_atomic.h | READ_ONCE | 6 |
| io_uring/fdinfo.c | common_tracking_show_fdinfo | 2 |
| include/linux/compiler.h | data_race | 2 |
| include/linux/minmax.h | min | 2 |
| include/linux/io_uring.h | io_uring_get_opcode | 1 |
| kernel/locking/rtmutex_api.c | mutex_trylock | 1 |
| kernel/sys.c | getrusage | 1 |
| io_uring/filetable.h | io_slot_file | 1 |
| fs/seq_file.c | seq_file_path | 1 |
| include/linux/xarray.h | xa_empty | 1 |
| include/linux/xarray.h | xa_for_each | 1 |
| io_uring/fdinfo.c | io_uring_show_cred | 1 |
| include/linux/list.h | hlist_for_each_entry | 1 |
| include/linux/task_work.h | task_work_pending | 1 |
| kernel/locking/mutex.c | mutex_unlock | 1 |
| include/linux/spinlock_rt.h | spin_lock | 1 |
| include/linux/list.h | list_for_each_entry | 1 |
| include/linux/spinlock_rt.h | spin_unlock | 1 |
| io_uring/fdinfo.c | napi_show_fdinfo | 1 |
