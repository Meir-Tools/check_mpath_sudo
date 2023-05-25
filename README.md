# check_mpath_sudo
cutom script based https://github.com/crphilipp/zabbix-agent-addons/blob/master/zabbix_scripts/check_mpath_sudo
# Install on linux
```
curl --ssl-no-revoke -L https://github.com/Meir-E/check_mpath_sudo/archive/refs/heads/main.zip > myfile.zip
unzip -j myfile.zip && chmod +x check_mpath_sudo.pl && rm myfile.zip README.md
```
# Run Example
```
./check_mpath_sudo.pl --mpath ssvm2./check_mpath_sudo.pl --mpath ssvm2  --pretty
```
# Run Example for Testing
```
./check_mpath_sudo.pl --mpath ssvm2./check_mpath_sudo.pl --mpath ssvm2  --pretty --t yes
```
