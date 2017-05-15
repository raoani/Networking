project_4 : rawhttpget
	chmod 777 ./rawhttpget
	sudo ethtool --offload  eth0  rx off  tx off
	sudo ethtool -K eth0 gso off gro off
	sudo iptables -A OUTPUT -p tcp --tcp-flags RST RST -j DROP

