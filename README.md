# sshcon

ssh connection manager script for Bash 5.1.0(1)-rc2 on Debian bullseye/sid

From Bash: wget https://github.com/jamescgooch/sshcon/releases/download/v1.0/sshcon && sudo chmod 777 sshcon && sed -i -e 's/\r$//' sshcon && ./sshcon

To start without dependency checks run: bash <(sed -n '82,$p' sshcon

For binary conversion after edits run: shc -f sshcon && mv sshcon.x /usr/bin/sshcon
