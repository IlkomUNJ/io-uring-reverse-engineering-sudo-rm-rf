# eventfd.c

| Library | Function utilized | Time Used |
| - | - | - |
| fs/eventfd.c | eventfd_ctx_put | 1 |
| mm/slub.c | kfree | 2 |
| include/linux/refcount.h | refcount_dec_and_test | 1 |
| kernel/rcu/tiny.c | call_rcu | 1 |
| fs/eventfd.c | eventfd_signal_mask | 2 |
| io_uring/eventfd.c | io_eventfd_put | 3 |
| lib/locking-selftest.c | rcu_read_unlock | 2 |
| include/linux/eventfd.h | eventfd_signal_allowed | 1 |
| include/linux/atomic/atomic-instrumented.h | atomic_fetch_or | 1 |
| kernel/rcu/tree.c | call_rcu_hurry | 1 |
| io_uring/io-wq.h | io_wq_current_is_worker | 1 |
| tools/testing/selftests/bpf/bpf_atomic.h | READ_ONCE | 1 |
| include/linux/rcupdate.h | rcu_read_lock | 1 |
| include/linux/rcupdate.h | rcu_dereference | 1 |
| io_uring/eventfd.c | io_eventfd_trigger | 1 |
| include/linux/refcount.h | refcount_inc_not_zero | 1 |
| io_uring/eventfd.c | io_eventfd_grab | 2 |
| io_uring/eventfd.c | io_eventfd_release | 2 |
| io_uring/eventfd.c | __io_eventfd_signal | 2 |
| include/linux/spinlock.h | spin_lock | 2 |
| include/linux/spinlock.h | spin_unlock | 2 |
| include/linux/rcupdate.h | rcu_dereference_protected | 2 |
| include/linux/lockdep.h | lockdep_is_held | 2 |
| include/linux/uaccess.h | copy_from_user | 1 |
| lib/decompress_unxz.c | kmalloc | 1 |
| fs/eventfd.c | eventfd_ctx_fdget | 1 |
| fs/bcachefs/trace.h | IS_ERR | 1 |
| include/linux/err.h | PTR_ERR | 1 |
| include/linux/refcount.h | refcount_set | 1 |
| include/linux/atomic/atomic-instrumented.h | atomic_set | 1 |
| include/linux/rcupdate.h | rcu_assign_pointer | 2 |
