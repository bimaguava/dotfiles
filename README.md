# Components
## Plymouth
the matrix themes you can find in ```/usr/share/plymouth/themes/matrix```

applying the themes

```
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/matrix/matrix.plymouth 100
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
```
