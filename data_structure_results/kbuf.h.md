# Defined in kbuf.h

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_buffer_list | union, struct list_head, struct io_uring_buf_ring | io_kbuf_inc_commit | io_uring/kbuf.c | function parameter |
| | | io_kbuf_commit | io_uring/kbuf.c | function parameter |
| | | io_buffer_add_list | io_uring/kbuf.c | function parameter |
| | | io_kbuf_recycle_legacy | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_provided_buffer_select | io_uring/kbuf.c | function parameter |
| | | io_provided_buffers_select | io_uring/kbuf.c | function parameter |
| | | io_ring_buffer_select | io_uring/kbuf.c | function parameter |
| | | io_buffer_select | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_ring_buffers_peek | io_uring/kbuf.c | function parameter |
| | | io_buffers_select | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_buffers_peek | io_uring/kbuf.c | declared local variable, function parameter |
| | | __io_put_kbuf_ring | io_uring/kbuf.c | function parameter, initialized local variable |
| | | __io_remove_buffers | io_uring/kbuf.c | function parameter |
| | | io_put_bl | io_uring/kbuf.c | function parameter |
| | | io_destroy_buffers | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_destroy_bl | io_uring/kbuf.c | function parameter |
| | | io_remove_buffers | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_add_buffers | io_uring/kbuf.c | function parameter |
| | | io_provide_buffers | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_register_pbuf_ring | io_uring/kbuf.c | function parameter |
| | | io_unregister_pbuf_ring | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_register_pbuf_status | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_pbuf_get_region | io_uring/kbuf.c | declared local variable, function parameter |
| io_buffer | struct list_head, __u64, __u32, __u16, __u16 | io_kbuf_recycle_legacy | io_uring/kbuf.c | declared local variable, function parameter |
| | | io_provided_buffer_select | io_uring/kbuf.c | function parameter |
| | | __io_remove_buffers | io_uring/kbuf.c | function parameter |
| | | io_add_buffers | io_uring/kbuf.c | declared local variable, function parameter |
| | | init_bufs | tools/usb/ffs-aio-example/multibuff/device_app/aio_multibuff.c | function parameter |
| | | delete_bufs | tools/usb/ffs-aio-example/multibuff/device_app/aio_multibuff.c | function parameter |
| | | main | tools/usb/ffs-aio-example/multibuff/device_app/aio_multibuff.c | function parameter |
| buf_sel_arg | struct iovec, size_t, size_t, unsigned short, unsigned short | io_ring_buffers_peek | io_uring/kbuf.c | function parameter |
| | | io_buffers_select | io_uring/kbuf.c | function parameter |
| | | io_buffers_peek | io_uring/kbuf.c | function parameter |
| | | io_send_select_buffer | io_uring/net.c | function parameter, initialized local variable |
| | | io_recv_buf_select | io_uring/net.c | function parameter, initialized local variable |
