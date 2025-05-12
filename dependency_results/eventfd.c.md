# eventfd.c

| Library | Function utilized | Time Used |
| - | - | - |
| - | eventfd_ctx_put | 1 |
| - | kfree | 2 |
| - | refcount_dec_and_test | 1 |
| - | call_rcu | 1 |
| - | eventfd_signal_mask | 2 |
| - | io_eventfd_put | 3 |
| - | rcu_read_unlock | 2 |
| - | eventfd_signal_allowed | 1 |
| - | atomic_fetch_or | 1 |
| - | call_rcu_hurry | 1 |
| - | io_wq_current_is_worker | 1 |
| - | READ_ONCE | 1 |
| - | rcu_read_lock | 1 |
| - | rcu_dereference | 1 |
| - | io_eventfd_trigger | 1 |
| - | refcount_inc_not_zero | 1 |
| - | io_eventfd_grab | 2 |
| - | io_eventfd_release | 2 |
| - | __io_eventfd_signal | 2 |
| - | spin_lock | 2 |
| - | spin_unlock | 2 |
| - | rcu_dereference_protected | 2 |
| - | lockdep_is_held | 2 |
| - | copy_from_user | 1 |
| - | kmalloc | 1 |
| - | eventfd_ctx_fdget | 1 |
| - | IS_ERR | 1 |
| - | PTR_ERR | 1 |
| - | refcount_set | 1 |
| - | atomic_set | 1 |
| - | rcu_assign_pointer | 2 |
