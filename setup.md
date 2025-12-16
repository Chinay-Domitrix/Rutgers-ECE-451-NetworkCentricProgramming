# Setup 

1. If you don't have a laptop, please contact me. We can see about a loaner if possible.

1. If you have Windows, you should install WSL (Windows Subsystem for Linux).
   This will allow you to use Linux on your laptop, with about 1GB of space, plug whatever you use.

1. If you have a Mac you may use it for much of the course. But for reverse engineering code we will use Intel assembler,
   so you will have to use either the vlab, or GCP server on Google cloud.

1. Sign up for Google GCP: https://cloud.google.com/edu/students?hl=en

1. As a Rutgers student or professor, we are all entitled to Colab Pro, which will give you 100 units/month of computation on colab, a nice benefit. How do we sign up for this? [TBD, help!] 

1. On any linux machine you set up, you will need software. On GCP or Colab, we will use a departmental drive so you don't have to install all the software. However, it's still a great idea to learn to install it yourself. And if you want to install on WSL you will have to. Here is a list of what we will be using (may grow):
  - gcc/g++
  - gdb (debugger)
  - git (version control)

```bash
sudo apt update
sudo apt install -y build-essential g++ gdb git cmake pkg-config \
  libssl-dev openssh-client openssh-server \
  libc6-dev libpthread-dev zlib1g-dev \
  valgrind strace ltrace \
  net-tools iproute2 tcpdump netcat \
  curl wget
```
