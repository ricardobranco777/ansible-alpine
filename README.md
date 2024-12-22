# ansible-alpine

Ansible configuration for Alpine Linux 3.21

```
setup-alpine
setup-desktop
```

Check:
`ansible-playbook -v -C -i inventory main.yml`

Run with:
`ansible-playbook -v -i inventory main.yml`

More information:

  - [Wiki](https://wiki.alpinelinux.org/wiki/How_to_get_regular_stuff_working)
  - [Musl vs Glibc](https://wiki.musl-libc.org/functional-differences-from-glibc.html)
  - [Glibc](https://wiki.alpinelinux.org/wiki/Running_glibc_programs)
