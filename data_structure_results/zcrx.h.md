# Defined in zcrx.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_zcrx_area | struct net_iov_area, struct io_zcrx_ifq, atomic_t, , bool, u16, struct page, unsigned long, , spinlock_t freelist_lock, u32, u32 | __io_zcrx_unmap_area | io_uring/zcrx.c | function parameter |
| | | io_zcrx_unmap_area | io_uring/zcrx.c | function parameter |
| | | io_zcrx_map_area | io_uring/zcrx.c | function parameter |
| | | io_get_user_counter | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_iov_page | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_free_area | io_uring/zcrx.c | function parameter |
| | | io_zcrx_create_area | io_uring/zcrx.c | function parameter, declared local variable |
| | | __io_zcrx_get_free_niov | io_uring/zcrx.c | function parameter |
| | | io_zcrx_return_niov_freelist | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_scrub | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_ring_refill | io_uring/zcrx.c | function parameter, declared local variable |
| | | io_zcrx_refill_slow | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_pp_zc_destroy | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_queue_cqe | io_uring/zcrx.c | function parameter, declared local variable |
| | | io_zcrx_alloc_fallback | io_uring/zcrx.c | function parameter |
| | | io_zcrx_copy_chunk | io_uring/zcrx.c | initialized local variable, function parameter |
| io_zcrx_ifq | struct io_ring_ctx, struct io_zcrx_area, , spinlock_t rq_lock, struct io_uring, struct io_uring_zcrx_rqe, u32, u32, , u32, struct device, struct net_device, netdevice_tracker, spinlock_t, struct mutex | __io_zcrx_unmap_area | io_uring/zcrx.c | function parameter |
| | | io_zcrx_unmap_area | io_uring/zcrx.c | function parameter |
| | | io_zcrx_map_area | io_uring/zcrx.c | function parameter |
| | | io_allocate_rbuf_ring | io_uring/zcrx.c | function parameter |
| | | io_free_rbuf_ring | io_uring/zcrx.c | function parameter |
| | | io_zcrx_create_area | io_uring/zcrx.c | function parameter |
| | | io_zcrx_drop_netdev | io_uring/zcrx.c | function parameter |
| | | io_close_queue | io_uring/zcrx.c | function parameter |
| | | io_zcrx_ifq_free | io_uring/zcrx.c | function parameter |
| | | io_register_zcrx_ifq | io_uring/zcrx.c | function parameter, declared local variable |
| | | io_unregister_zcrx_ifqs | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_scrub | io_uring/zcrx.c | function parameter |
| | | io_zcrx_rqring_entries | io_uring/zcrx.c | function parameter |
| | | io_zcrx_get_rqe | io_uring/zcrx.c | function parameter |
| | | io_zcrx_ring_refill | io_uring/zcrx.c | function parameter |
| | | io_zcrx_refill_slow | io_uring/zcrx.c | function parameter |
| | | io_pp_zc_alloc_netmems | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_pp_zc_init | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_pp_zc_destroy | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_pp_uninstall | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_queue_cqe | io_uring/zcrx.c | function parameter |
| | | io_zcrx_copy_chunk | io_uring/zcrx.c | function parameter |
| | | io_zcrx_copy_frag | io_uring/zcrx.c | function parameter |
| | | io_zcrx_recv_frag | io_uring/zcrx.c | function parameter |
| | | io_zcrx_recv_skb | io_uring/zcrx.c | initialized local variable, function parameter |
| | | io_zcrx_tcp_recvmsg | io_uring/zcrx.c | function parameter |
| | | io_zcrx_recv | io_uring/zcrx.h | function parameter |
