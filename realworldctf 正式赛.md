比赛地址：https://realworldctf.com/

题目网盘备份

链接：https://pan.baidu.com/s/1u4-BhWEktUw8Rg4vFdw4Sg 
提取码：xmxm

## `Quadrennial`

Score: *33*

`Check-in`

Time and the dragons always tell the real.

![Quadrennial](../../../picture/realworldctf 正式赛/Quadrennial.png)

Tip：4 words in the right order/use the underscore to connect the truth and put it in the flag format rwctf{something}.

## `SVME`

Score: *102*

`Clone-and-Pwn`, `Virtual Machine`, `difficulty:baby`

Professor Terence Parr has taught us [how to build a virtual machine](https://www.slideshare.net/parrt/how-to-build-a-virtual-machine). Now it's time to break it!

```
nc 47.243.140.252 1337
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/svme_9495bfd34dcaea7af748f1138d5fc25e.tar.gz)


## `Hack into Skynet`

Score: *114*

`Web`, `difficulty:Schrödinger`

Hack into skynet to save the world, which way do you prefer?

Note: Skynet is a blackbox detection engine which is not provided. But you don't have to guess.

Note2: Scanner or sqlmap **NOT REQUIRED** to solve this challenge, please do not use scanners.

Target: 47.242.21.212:8081-8086/TCP

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/hack_into_skynet_843e0c58997f52e3a65ca9b4c64f2cec.tar.gz)


## `hso groupie`

Score: *500*

`Clone-and-Pwn`, `difficulty:hard`

Help check how secure our latest PaaS (Pdftohtml-as-a-Service) is!

![hso_groupie_8493e7780b3e598201211dbc71e0984a](../../../picture/realworldctf 正式赛/hso_groupie_8493e7780b3e598201211dbc71e0984a.jpg)

Pick your favorite bug from [this bloody list](https://gitlab.freedesktop.org/poppler/poppler/-/commits/master/poppler/JBIG2Stream.cc), or really, just exploit *that bug* so your exploit would also work on latest Poppler [1] and maybe even KItinerary.

The container image is also available on [Docker Hub](https://hub.docker.com/hsogroupie/pdftohtml).

[1] Yeah, turns out propagating bug fixes between different Clone-and-Own codebases takes time :)

```
socat -t90 stdio tcp-connect:47.242.147.191:31337
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/hso-groupie_e12364e01f315138be56450b27487d09715774d769cfacac33f834fe05a02f28.tar.gz)

## `Desperate Cat`

Score: *500*

`Web`, `difficulty:hard`

What kind of bad thoughts can kittens have?

```
nc 47.243.235.228 9999
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/DesperateCat_06de0713d3d9e5ba2dd66e25ea350b8d.tar.gz)

## `FLAG`

Score: *500*

`Pwn`, `difficulty:normal`

FreeRTOS+LwIP+ARM+GoAhead

I don't want another backdoor ctf. So I have to say: "There is a backdoor in challange"

The default account in attachment is admin:admin

```
nc 8.210.44.156 31337
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/flag_36a6ce00a9bf39c377b0e1d0a2c1f358.tar.gz)

## `Treasure Hunter`

Score: *320*

`Crypto`, `difficulty:Schrödinger`

There is a key and a treasure chest in Trap Room, whether you touch the treasure chest or the key you will be trapped, so how do you get the treasure?

It's treasure hunter show time!

```
nc 47.243.235.111 20000
```

faucet on port 8080, geth on port 8545

## `API6`

Score: *477*

`Web`, `Clone-and-Pwn`, `difficulty:hard`

Apache APISIX lets you build Cloud-Native Microservices API gateways, delivering the ultimate performance, open source, scalable platform and **free remote code execution bugs** for all your APIs and microservices.

```
nc 47.243.183.218 31337
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/API6_77ba5ac86cf4ab83411a3cf3f08ddff4.tar.gz)

## `QLaaS`

Score: *451*

`Clone-and-Pwn`, `difficulty:Schrödinger`

Qiling as a Service.

```
nc 47.242.149.197 7600
```

[QLaaS_61a8e641694e10ce360554241bdda977.tar.gz](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/QLaaS_61a8e641694e10ce360554241bdda977.tar.gz)

Note: read flag using `/readflag`

## `The Rise of Sky`

Score: *500*

`Pwn`, `difficulty:normal`

Lo and behold, here be live streaming on the SKY810.

```
nc 47.242.246.203 9999
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/TheRiseOfSky_243b31708c56461abf307e572c3c4472.bin)

## `Black Box`

Score: *500*

`Virtual Machine`, `Clone-and-Pwn`, `difficulty:normal`

This is a challenge that is two years late about CVE-2020-14364. Enjoy it :)

```
nc 47.243.43.90 1234
```

## `Trust or Not`

Score: *500*

`Reverse`, `difficulty:normal`

We have lost some of our files and cannot retrieve the plaintext data originally stored.

```
nc 47.242.114.24 7788
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/Trust_or_not_fa542592446c43678f685913495da668.tar.gz)

## `RWDN`

Score: *215*

`Web`, `difficulty:baby`

Solve this challenge to make Shang Abi 's social credit +10000 👆🙂👇

http://47.243.75.225:31337/

## `Who Moved My Block`

Score: *276*

`Clone-and-Pwn`, `difficulty:baby`

On Linux, network block device (NBD) is a network protocol that can be used to forward a block device (typically a hard disk or partition) from one machine to a second machine. As an example, a local machine can access a hard disk drive that is attached to another computer.

https://github.com/NetworkBlockDevice/nbd

```
nc 47.242.113.232 31337
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/WhoMovedMyBlock_471d96239f86cb3f7c61991b44d74623.zip)

## `Wheels on the Bus`

Score: *500*

`Clone-and-Pwn`, `difficulty:Schrödinger`

[The wheels on the bus](https://youtu.be/e_04ZrNroTo) go round and round,

round and round,

round and round.

The wheels on the bus go round and round,

The **Bus** leads to root.

Hint: ss -ln told me something is listening on 0.0.0.0:3000 🤔

Hint2: The bug we exploited is not in those victronenergy/dbus-* Python codebases.

```
nc 47.243.164.190 6666
```

## `Secured Java`

Score: *357*

`Misc`, `Pwn`, `difficulty:Schrödinger`

I just found a safe way to run untrusted Java code!

```
nc 139.224.248.65 1337
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/secured-java_2e1e157c03d1dc96be8113ac21269059.tar.gz)

## `UntrustZone`

Score: *500*

`Pwn`, `difficulty:normal`

It is clearly not worth your trust.

The default username is root.

```
nc 47.243.205.105 8899
```

[attachment](https://realworldctf-attachment.oss-accelerate.aliyuncs.com/UnstrustZone_d9d2151c29fa340f80f38197492001fe.tar.gz)

The start script of challenge

```
qemu-system-aarch64 \
        -nographic \
        -smp 2 \
        -machine virt,secure=on,gic-version=3,virtualization=false \
        -cpu cortex-a57 \
        -d unimp -semihosting-config enable=on,target=native \
        -m 1024 \
        -bios bl1.bin \
        -initrd rootfs.cpio.gz \
        -kernel Image -no-acpi \
        -append console="ttyAMA0,38400 keep_bootcon root=/dev/vda2  -object rng-random,filename=/dev/urandom,id=rng0 -device virtio-rng-pci,rng=rng0,max-bytes=1024,period=1000" \
        -netdev user,id=vmnic -device virtio-net-device,netdev=vmnic \
        -no-reboot \
        -monitor null
```
