# Defined in net.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_shutdown | struct file, int | io_shutdown_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_shutdown | io_uring/net.c | function parameter, initialized local variable |
| io_accept | struct file, struct sockaddr __user, int __user, int, int, u32, unsigned long | io_accept_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_accept | io_uring/net.c | function parameter, initialized local variable |
| io_socket | struct file, int, int, int, int, u32, unsigned long | io_socket_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_socket | io_uring/net.c | function parameter, initialized local variable |
| io_connect | struct file, struct sockaddr __user, int, bool, bool | io_connect_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_connect | io_uring/net.c | function parameter, initialized local variable |
| io_bind | struct file, int | io_bind_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_bind | io_uring/net.c | function parameter, initialized local variable |
| io_listen | struct file, int | io_listen_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_listen | io_uring/net.c | function parameter, initialized local variable |
| io_sr_msg | struct file, union, struct compat_msghdr __user, struct user_msghdr __user, void __user | io_mshot_prep_retry | io_uring/net.c | function parameter, initialized local variable |
| | | io_compat_msg_copy_hdr | io_uring/net.c | function parameter, initialized local variable |
| | | io_msg_copy_hdr | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_setup | io_uring/net.c | function parameter, initialized local variable |
| | | io_sendmsg_setup | io_uring/net.c | function parameter, initialized local variable |
| | | io_sendmsg_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_finish | io_uring/net.c | function parameter, initialized local variable |
| | | io_sendmsg | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_select_buffer | io_uring/net.c | function parameter, initialized local variable |
| | | io_send | io_uring/net.c | function parameter, initialized local variable |
| | | io_recvmsg_prep_setup | io_uring/net.c | function parameter, initialized local variable |
| | | io_recvmsg_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_recv_finish | io_uring/net.c | function parameter, initialized local variable |
| | | io_recvmsg_prep_multishot | io_uring/net.c | function parameter |
| | | io_recvmsg_multishot | io_uring/net.c | function parameter |
| | | io_recvmsg | io_uring/net.c | function parameter, initialized local variable |
| | | io_recv_buf_select | io_uring/net.c | function parameter, initialized local variable |
| | | io_recv | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_zc_cleanup | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_zc_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_zc_import | io_uring/net.c | function parameter, initialized local variable |
| | | io_send_zc | io_uring/net.c | function parameter, initialized local variable |
| | | io_sendmsg_zc | io_uring/net.c | function parameter, initialized local variable |
| | | io_sendrecv_fail | io_uring/net.c | function parameter, initialized local variable |
| io_recvzc | struct file, unsigned, u16, u32, struct io_zcrx_ifq | io_recvzc_prep | io_uring/net.c | function parameter, initialized local variable |
| | | io_recvzc | io_uring/net.c | function parameter, initialized local variable |
| io_recvmsg_multishot_hdr | struct io_uring_recvmsg_out, struct sockaddr_storage | io_recvmsg_multishot | io_uring/net.c | function parameter |
