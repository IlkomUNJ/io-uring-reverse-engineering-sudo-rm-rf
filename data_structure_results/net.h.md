# Defined in net.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_async_msghdr | #if, struct iou_vec, , , int, struct iovec, __kernel_size_t, __kernel_size_t, struct sockaddr __user, struct msghdr, struct sockaddr_storage, , , ,  | io_ring_ctx_alloc | io_uring/io_uring.c | function parameter |
| | | io_netmsg_iovec_free | io_uring/net.c | function parameter |
| | | io_netmsg_recycle | io_uring/net.c | function parameter, initialized local variable |
| | | io_mshot_prep_retry | io_uring/net.c | function parameter |
| | | io_net_import_vec | io_uring/net.c | function parameter |
| | | io_compat_msg_copy_hdr | io_uring/net.c | function parameter |
| | | io_msg_copy_hdr | io_uring/net.c | function parameter |
| | | io_sendmsg_recvmsg_cleanup | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_setup | io_uring/net.c | function parameter, initialized local variable |
| | | io_sendmsg_setup | io_uring/net.c | function parameter, initialized local variable |
| | | io_bundle_nbufs | io_uring/net.c | function parameter |
| | | io_send_finish | io_uring/net.c | function parameter |
| | | io_sendmsg | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_select_buffer | io_uring/net.c | function parameter |
| | | io_send | io_uring/net.c | function parameter, initialized local variable |
| | | io_recvmsg_mshot_prep | io_uring/net.c | function parameter |
| | | io_recvmsg_copy_hdr | io_uring/net.c | function parameter |
| | | io_recvmsg_prep_setup | io_uring/net.c | function parameter, declared local variable |
| | | io_recv_finish | io_uring/net.c | function parameter |
| | | io_recvmsg_prep_multishot | io_uring/net.c | function parameter |
| | | io_recvmsg_multishot | io_uring/net.c | function parameter |
| | | io_recvmsg | io_uring/net.c | function parameter, initialized local variable |
| | | io_recv_buf_select | io_uring/net.c | function parameter |
| | | io_recv | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_zc_cleanup | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_zc_prep | io_uring/net.c | function parameter, declared local variable |
| | | io_send_zc_import | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_zc | io_uring/net.c | function parameter, initialized local variable |
| | | io_sendmsg_zc | io_uring/net.c | function parameter, initialized local variable |
| | | io_connect_prep | io_uring/net.c | function parameter, declared local variable |
| | | io_connect | io_uring/net.c | function parameter, initialized local variable |
| | | io_bind_prep | io_uring/net.c | function parameter, declared local variable |
| | | io_bind | io_uring/net.c | function parameter, initialized local variable |
| | | io_netmsg_cache_free | io_uring/net.c | function parameter, initialized local variable |
