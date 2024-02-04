Takes a stock ubuntu server on a Le Potato and installs XFCE, Chromium, and runs juice-shop on localhost:3000. Once everything is installed, no internet is necessary

To use, update the IP address of the potato in inventory, then run

``` bash
ansible-playbook lePotato-Ubuntu-XFCE-Juice-Shop.yaml -u ubuntu -k
```
