# Defined in fs.c

| Structure Name | Attributes | Caller Functions | Caller Source | Usage |
| - | - | - | - | - |
| io_rename | struct file, int, int, struct filename, struct filename, int | io_renameat_prep | io_uring/fs.c | initialized local variable, function parameter |
| | | io_renameat | io_uring/fs.c | initialized local variable, function parameter |
| | | io_renameat_cleanup | io_uring/fs.c | initialized local variable, function parameter |
| io_unlink | struct file, int, int, struct filename | io_unlinkat_prep | io_uring/fs.c | initialized local variable, function parameter |
| | | io_unlinkat | io_uring/fs.c | initialized local variable, function parameter |
| | | io_unlinkat_cleanup | io_uring/fs.c | initialized local variable, function parameter |
| io_mkdir | struct file, int, umode_t, struct filename | io_mkdirat_prep | io_uring/fs.c | initialized local variable, function parameter |
| | | io_mkdirat | io_uring/fs.c | initialized local variable, function parameter |
| | | io_mkdirat_cleanup | io_uring/fs.c | initialized local variable, function parameter |
| io_link | struct file, int, int, struct filename, struct filename, int | io_symlinkat_prep | io_uring/fs.c | initialized local variable, function parameter |
| | | io_symlinkat | io_uring/fs.c | initialized local variable, function parameter |
| | | io_linkat_prep | io_uring/fs.c | initialized local variable, function parameter |
| | | io_linkat | io_uring/fs.c | initialized local variable, function parameter |
| | | io_link_cleanup | io_uring/fs.c | initialized local variable, function parameter |
