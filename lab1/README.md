# Lab 1 - Ship it

- **Image:** `ghcr.io/ranbirsingh0091/lab1-web:1.0`
- **Digest:** `sha256:368ff695aa6df78f29c5fc8d2ccb56b4bc6e3243a6ced86d4e2725d139ea3091`
- **Platforms:** linux/amd64, linux/arm64
- **Partner's image I ran:** `ghcr.io/ranbirsingh0091/lab1-web:1.0` (digest matched: NO)

![My partner's image running on my laptop](partner-run.png)

## Answers

### 1. Where does the kernel used by your containers come from on your laptop?


My `docker info` output:

```text
Docker Desktop | kernel 6.6.114.1-microsoft-standard-WSL2 | x86_64 | 8 CPUs | 8210448384 bytes
```

My Alpine `uname -r` output:

```text
6.6.114.1-microsoft-standard-WSL2
```

My Ubuntu `uname -r` output:

```text
6.6.114.1-microsoft-standard-WSL2
```

Both containers reported the same kernel version, showing that containers share
the host VM's Linux kernel.

### 2. What is the difference between `lab1-web:1.0` and `mypage`?


### 3. Why did the edit survive `docker stop` but not `docker rm`?


### 4. Why is the image much larger than the HTML page?