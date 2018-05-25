# install-youtube-dl
How to instal youtube-dl

<img src="https://github.com/moeslimdecoded/install-youtube-dl/blob/master/install-youtube-dl.png">

Jika terdapat error pada saat pembuatan virtual emulator misal kasus ini muncul di ubuntu 18.04 LTS yaitu
/dev/kvm device: permission denied

yaitu dengan menginstall kan paket berikut:
```
bash@tracker:~$ sudo apt install qemu-kvm
```
setelah itu konfig tambahkan username komputer kedalam group kvm seperti berikut
```
bash@tracker:~$ sudo adduser [nama-user-ubuntu] kvm
```
