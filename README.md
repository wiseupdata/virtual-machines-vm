<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="Wise Up Data's Instagram" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wiseupdata/main/assets/instagram.png" />   
</a> 
<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="wise Up Data's Discord" width="22px" src="https://github.com/wiseupdata/wiseupdata/blob/main/assets/discord.svg" />
</a>
<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="wise Up Data | Twitter" width="22px" src="https://github.com/wiseupdata/wiseupdata/blob/main/assets/twitter.svg" />
</a>
<a href="https://github.com/wiseupdata/wiseupdata">
  <img align="left" alt="wise Up Data's LinkedIN" width="22px" src="https://raw.githubusercontent.com/wiseupdata/wiseupdata/200536ac97c85161cdfea6de4fc9b271ba197c2d/assets/linkedin.svg" />
</a>

![visitors](https://visitor-badge.glitch.me/badge?page_id=wiseupdata.virtual-machines-vm&left_color=green&right_color=black)
![license](https://img.shields.io/github/license/wiseupdata/virtual-machines-vm)

---

<a name="readme-top"></a>

<details>
<summary>
    Install GUI RDP, remote desktop in one VM 🚀️
</summary>

<details>
<summary>
    Information 
</summary>

> X2Go is a remote desktop software solution that enables you to access graphical desktops of Linux servers over a low bandwidth connection. It is a fast and lightweight alternative to other remote desktop protocols, such as VNC or RDP.
> 
> X2Go is a good choice for setting up RDP on your Ubuntu VM running in Cloud for several reasons:
> 
> - It is open-source and free.
> - It provides a secure remote desktop solution by using the SSH protocol for encryption.
> - It supports various desktop environments, such as Xfce, Mate, LXDE, KDE, and more.
> - It is easy to install and configure on Ubuntu.
> - It has a low memory footprint, making it suitable for low-spec VMs.
> 
> Overall, X2Go is a reliable and efficient option for setting up RDP on your Ubuntu VM in Cloud.

</details>


<details>
<summary>
    Installation 🚀️
</summary>


### Let's update the Ubuntu system 👀️

```
sudo apt update
sudo apt upgrade
```

<img align="center" alt="gif" src="assets/update.gif" width="700" />
</img>
<br>

### Install the X2Go server

```
sudo apt install software-properties-common
sudo add-apt-repository ppa:x2go/stable
sudo apt update
sudo apt install x2goserver x2goserver-xsession
```

<img align="center" alt="gif" src="assets/x2go.gif" width="700" />
</img>
<br>

### Install the xfce4 server

```
sudo apt install xfce4
```

<img align="center" alt="gif" src="assets/xfce4.gif" width="700" />
</img>
<br>

### Start the X2Go server

```
sudo systemctl start x2goserver
```

<img align="center" alt="gif" src="assets/x2goserver.gif" width="700" />

<br>
<br>

</details>

<details>
<summary>
    Extra - Install the X2Go Client in the Windows 11 🚀️
</summary>

### Let's update the Ubuntu system 👀️

```
sudo apt update
sudo apt upgrade
```

<img align="center" alt="gif" src="assets/update.gif" width="700" />
</img>
<br>

</details>

</details>



# References 🎉️

1. [Wise Up Data](https://github.com/wiseupdata)

<br><br>
---

#### Maintainer 🤗 👨‍💻

Sivio Liborio

📧 silvio.liborio@wiseupdata.com

<a href="https://www.linkedin.com/in/silvio-de-melo-liborio">silvio-de-melo-liborio <img align="left" alt="LinkedIN" width="18px" src="https://raw.githubusercontent.com/wiseupdata/wsl-latest/main/assets/linkedin.svg" />
</a>
