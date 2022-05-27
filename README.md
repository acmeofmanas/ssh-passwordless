#assume sshd configured and able to access host using password
ssh-keygen -t rsa -b 4096
# ack with return for location
ssh-copy-id -i /root/.ssh/id_rsa.pub root@10.56.238.62
