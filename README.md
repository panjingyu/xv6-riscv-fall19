安装时修改了qemu-4.1.0/configure，将ssh_get_server_publickey改为ssh_get_publickey，并删除了-DHAVE_SSH_0_8（影响block/ssh.c的编译）。
