# Defined in io-wq.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_worker | refcount_t, unsigned long, struct hlist_nulls_node, struct list_head, struct task_struct, struct io_wq, struct io_wq_acct, , struct io_wq_work, raw_spinlock_t, , struct completion, , unsigned long, struct callback_head, int, , union, struct rcu_head, struct delayed_work | io_worker_get | io_uring/io-wq.c | function parameter |
| | | io_worker_release | io_uring/io-wq.c | function parameter |
| | | io_wq_get_acct | io_uring/io-wq.c | function parameter |
| | | io_wq_worker_stopped | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_worker_cancel_cb | io_uring/io-wq.c | function parameter |
| | | io_task_worker_match | io_uring/io-wq.c | function parameter |
| | | io_worker_exit | io_uring/io-wq.c | function parameter |
| | | __must_hold | io_uring/io-wq.c | function parameter, declared local variable |
| | | io_wq_inc_running | io_uring/io-wq.c | function parameter |
| | | create_worker_cb | io_uring/io-wq.c | function parameter |
| | | io_queue_worker_create | io_uring/io-wq.c | function parameter |
| | | io_wq_dec_running | io_uring/io-wq.c | function parameter |
| | | __io_worker_busy | io_uring/io-wq.c | function parameter |
| | | __io_worker_idle | io_uring/io-wq.c | function parameter |
| | | io_assign_current_work | io_uring/io-wq.c | function parameter |
| | | io_worker_handle_work | io_uring/io-wq.c | function parameter |
| | | io_wq_worker | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_worker_running | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_worker_sleeping | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_init_new_worker | io_uring/io-wq.c | function parameter |
| | | io_should_retry_thread | io_uring/io-wq.c | function parameter |
| | | queue_create_worker_retry | io_uring/io-wq.c | function parameter |
| | | create_worker_cont | io_uring/io-wq.c | function parameter |
| | | io_workqueue_create | io_uring/io-wq.c | function parameter, initialized local variable |
| | | create_io_worker | io_uring/io-wq.c | function parameter, declared local variable |
| | | bool | io_uring/io-wq.c | function parameter |
| | | io_wq_worker_wake | io_uring/io-wq.c | function parameter |
| | | __io_wq_worker_cancel | io_uring/io-wq.c | function parameter |
| | | io_wq_worker_cancel | io_uring/io-wq.c | function parameter |
| | | io_task_work_match | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_tw_create | io_uring/io-wq.c | function parameter |
| | | io_wq_worker_affinity | io_uring/io-wq.c | function parameter |
| io_wq_acct | raw_spinlock_t, , unsigned, unsigned, atomic_t, , struct hlist_nulls_head, , struct list_head, , raw_spinlock_t, struct io_wq_work_list, unsigned long | io_worker_cancel_cb | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_worker_exit | io_uring/io-wq.c | function parameter, initialized local variable |
| | | __io_acct_run_queue | io_uring/io-wq.c | function parameter |
| | | io_acct_run_queue | io_uring/io-wq.c | function parameter |
| | | io_acct_activate_free_worker | io_uring/io-wq.c | function parameter |
| | | io_wq_create_worker | io_uring/io-wq.c | function parameter |
| | | io_wq_inc_running | io_uring/io-wq.c | function parameter, initialized local variable |
| | | create_worker_cb | io_uring/io-wq.c | function parameter, declared local variable |
| | | io_queue_worker_create | io_uring/io-wq.c | function parameter |
| | | io_wq_dec_running | io_uring/io-wq.c | function parameter, initialized local variable |
| | | __io_worker_busy | io_uring/io-wq.c | function parameter |
| | | __io_worker_idle | io_uring/io-wq.c | function parameter |
| | | io_get_next_work | io_uring/io-wq.c | function parameter |
| | | io_worker_handle_work | io_uring/io-wq.c | function parameter |
| | | io_wq_worker | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_init_new_worker | io_uring/io-wq.c | function parameter |
| | | create_worker_cont | io_uring/io-wq.c | function parameter, declared local variable |
| | | io_workqueue_create | io_uring/io-wq.c | function parameter, initialized local variable |
| | | create_io_worker | io_uring/io-wq.c | function parameter |
| | | io_acct_for_each_worker | io_uring/io-wq.c | function parameter |
| | | io_wq_insert_work | io_uring/io-wq.c | function parameter |
| | | io_wq_enqueue | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_remove_pending | io_uring/io-wq.c | function parameter |
| | | io_acct_cancel_pending_work | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_pending_work | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_acct_cancel_running_work | io_uring/io-wq.c | function parameter |
| | | io_wq_hash_wake | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_create | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_max_workers | io_uring/io-wq.c | function parameter, declared local variable |
| io_wq | unsigned long, , free_work_fn, io_wq_work_fn, , struct io_wq_hash, , atomic_t, struct completion, , struct hlist_node, , struct task_struct, , struct io_wq_acct, , struct wait_queue_entry, , struct io_wq_work, , cpumask_var_t | io_async_cancel_one | io_uring/cancel.c | function parameter |
| | | io_get_acct | io_uring/io-wq.c | function parameter |
| | | io_work_get_acct | io_uring/io-wq.c | function parameter |
| | | io_worker_ref_put | io_uring/io-wq.c | function parameter |
| | | io_worker_cancel_cb | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_worker_exit | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_create_worker | io_uring/io-wq.c | function parameter |
| | | create_worker_cb | io_uring/io-wq.c | function parameter, declared local variable |
| | | io_queue_worker_create | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_dec_running | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wait_on_hash | io_uring/io-wq.c | function parameter |
| | | io_get_next_work | io_uring/io-wq.c | function parameter |
| | | io_worker_handle_work | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_worker | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_init_new_worker | io_uring/io-wq.c | function parameter |
| | | create_worker_cont | io_uring/io-wq.c | function parameter, declared local variable |
| | | create_io_worker | io_uring/io-wq.c | function parameter |
| | | io_wq_for_each_worker | io_uring/io-wq.c | function parameter |
| | | io_run_cancel | io_uring/io-wq.c | function parameter |
| | | io_wq_insert_work | io_uring/io-wq.c | function parameter |
| | | io_wq_enqueue | io_uring/io-wq.c | function parameter |
| | | io_wq_remove_pending | io_uring/io-wq.c | function parameter |
| | | io_acct_cancel_pending_work | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_pending_work | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_running_work | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_cb | io_uring/io-wq.c | function parameter |
| | | io_wq_hash_wake | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_exit_start | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_tw_create | io_uring/io-wq.c | function parameter |
| | | io_wq_exit_workers | io_uring/io-wq.c | function parameter |
| | | io_wq_destroy | io_uring/io-wq.c | function parameter |
| | | io_wq_put_and_exit | io_uring/io-wq.c | function parameter |
| | | __io_wq_cpu_online | io_uring/io-wq.c | function parameter |
| | | io_wq_cpu_online | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_cpu_offline | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_cpu_affinity | io_uring/io-wq.c | function parameter |
| | | io_wq_max_workers | io_uring/io-wq.c | function parameter |
| | | bool | io_uring/io-wq.h | function parameter |
| | | io_queue_iowq | io_uring/io_uring.c | function parameter |
| | | io_ring_exit_work | io_uring/io_uring.c | function parameter |
| | | io_uring_try_cancel_iowq | io_uring/io_uring.c | function parameter |
| | | io_uring_try_cancel_requests | io_uring/io_uring.c | function parameter |
| | | io_uring_cancel_generic | io_uring/io_uring.c | function parameter |
| | | io_register_iowq_max_workers | io_uring/register.c | function parameter |
| | | __io_uring_free | io_uring/tctx.c | function parameter |
| | | io_uring_alloc_task_context | io_uring/tctx.c | function parameter |
| | | __io_uring_add_tctx_node | io_uring/tctx.c | function parameter |
| | | io_uring_clean_tctx | io_uring/tctx.c | initialized local variable |
| io_cb_cancel_data | work_cancel_fn, void, int, int, bool | create_worker_cont | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_enqueue | io_uring/io-wq.c | function parameter, initialized local variable |
| | | __io_wq_worker_cancel | io_uring/io-wq.c | function parameter |
| | | io_wq_worker_cancel | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_acct_cancel_pending_work | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_pending_work | io_uring/io-wq.c | function parameter |
| | | io_acct_cancel_running_work | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_running_work | io_uring/io-wq.c | function parameter |
| | | io_wq_cancel_cb | io_uring/io-wq.c | function parameter, initialized local variable |
| | | io_wq_destroy | io_uring/io-wq.c | function parameter, initialized local variable |
| online_data | unsigned int, bool | io_wq_worker_affinity | io_uring/io-wq.c | function parameter, initialized local variable |
| | | __io_wq_cpu_online | io_uring/io-wq.c | function parameter, initialized local variable |
