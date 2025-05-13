# Defined in cancel.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_cancel | struct file, u64, u32, s32, u8 | SYSCALL_DEFINE3 | fs/aio.c | function parameter |
| | | io_async_cancel_prep | io_uring/cancel.c | function parameter, initialized local variable |
| | | io_async_cancel | io_uring/cancel.c | function parameter, initialized local variable |
