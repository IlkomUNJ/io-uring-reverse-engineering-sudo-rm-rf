# Task 2: Dependency Injection

## SOURCES

### Core Source Files

- [io_uring.c](dependency_results/io_uring.c.md)
- [rw.c](dependency_results/rw.c.md)
- [io-wq.c](dependency_results/io-wq.c.md)
- [sqpoll.c](dependency_results/sqpoll.c.md)
- [poll.c](dependency_results/poll.c.md)
- [cancel.c](dependency_results/cancel.c.md)
- [timeout.c](dependency_results/timeout.c.md)
- [kbuf.c](dependency_results/kbuf.c.md)

### Networking Components

- [net.c](dependency_results/net.c.md)
- [zcrx.c](dependency_results/zcrx.c.md)
- [napi.c](dependency_results/napi.c.md)

### Resource Management

- [filetable.c](dependency_results/filetable.c.md)
- [rsrc.c](dependency_results/rsrc.c.md)
- [alloc_cache.c](dependency_results/alloc_cache.c.md)

### File System Operations

- [fs.c](dependency_results/fs.c.md)
- [openclose.c](dependency_results/openclose.c.md)
- [sync.c](dependency_results/sync.c.md)
- [xattr.c](dependency_results/xattr.c.md)

### Command and Interface Extensions

- [uring_cmd.c](dependency_results/uring_cmd.c.md)
- [msg_ring.c](dependency_results/msg_ring.c.md)
- [notif.c](dependency_results/notif.c.md)

### Specialized I/O Operations

- [splice.c](dependency_results/splice.c.md)
- [truncate.c](dependency_results/truncate.c.md)
- [statx.c](dependency_results/statx.c.md)

### System Integration Features

- [fdinfo.c](dependency_results/fdinfo.c.md)
- [memmap.c](dependency_results/memmap.c.md)
- [tctx.c](dependency_results/tctx.c.md)

### Synchronization Primitives

- [eventfd.c](dependency_results/eventfd.c.md)
- [futex.c](dependency_results/futex.c.md)
- [waitid.c](dependency_results/waitid.c.md)

### Internal Utilities

- [advise.c](dependency_results/advise.c.md)
- [epoll.c](dependency_results/epoll.c.md)
- [register.c](dependency_results/register.c.md)
- [nop.c](dependency_results/nop.c.md)

### Security and Verification Components

- [opdef.c](dependency_results/opdef.c.md)

## HEADERS

### Core Interface Headers

- [io_uring.h](dependency_results/io_uring.h.md)
- [opdef.h](dependency_results/opdef.h.md)
- [register.h](dependency_results/register.h.md)

### Resource Management Headers

- [refs.h](dependency_results/refs.h.md)
- [rsrc.h](dependency_results/rsrc.h.md)
- [filetable.h](dependency_results/filetable.h.md)
- [alloc_cache.h](dependency_results/filetable.h.md)

### I/O Processing Headers

- [rw.h](dependency_results/rw.h.md)
- [kbuf.h](dependency_results/kbuf.h.md)
- [splice.h](dependency_results/splice.h.md)
- [fs.h](dependency_results/fs.h.md)
- [net.h](dependency_results/net.h.md)
- [zcrx.h](dependency_results/zcrx.h.md)

### Event Management Headers

- [poll.h](dependency_results/poll.h.md)
- [epoll.h](dependency_results/epoll.h.md)
- [timeout.h](dependency_results/timeout.h.md)
- [napi.h](dependency_results/napi.h.md)
- [notif.h](dependency_results/notif.h.md)

### Synchronization Headers

- [futex.h](dependency_results/futex.h.md)
- [eventfd.h](dependency_results/eventfd.h.md)
- [waitid.h](dependency_results/waitid.h.md)
- [sync.h](dependency_results/sync.h.md)

### Command and Extension Headers

- [uring_cmd.h](dependency_results/uring_cmd.h.md)
- [msg_ring.h](dependency_results/msg_ring.h.md)
- [io-wq.h](dependency_results/io-wq.h.md)

### File Operation Headers

- [openclose.h](dependency_results/openclose.h.md)
- [statx.h](dependency_results/statx.h.md)
- [truncate.h](dependency_results/truncate.h.md)
- [xattr.h](dependency_results/xattr.h.md)
- [advise.h](dependency_results/advise.h.md)

### Memory Management Headers

- [memmap.h](dependency_results/memmap.h.md)
- [slist.h](dependency_results/slist.h.md)

### Runtime and Process Management Headers

- [tctx.h](dependency_results/tctx.h.md)
- [sqpoll.h](dependency_results/sqpoll.h.md)
- [nop.h](dependency_results/nop.h.md)

### Debugging and Monitoring Headers

- [fdinfo.h](dependency_results/fdinfo.h.md)
- [cancel.h](dependency_results/cancel.h.md)
