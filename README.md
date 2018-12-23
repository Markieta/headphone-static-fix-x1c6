# headphone-static-fix-x1c6
Fixes headphone audio static and crackling on the X1 Carbon (6th Gen) in Linux (Fedora 29)

The following is tested and working on Fedora 29, and should work on other operating systems that use systemd:

```bash
git clone https://github.com/Markieta/headphone-static-fix-x1c6.git
sudo cp headphone-static-fix-x1c6/headphone-static-fix-x1c6.service /etc/systemd/system/
sudo systemctl daemon-reload
sudo systemctl enable --now headphone-static-fix-x1c6.service
```
