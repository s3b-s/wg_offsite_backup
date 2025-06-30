# wg_offsite_backup
Tool to automate the control of Wireguard on VPS server that acts as a jump host for two systems doing offsite backups to each other.
It allows to send control files to VPS server which are then red by the hosts to read and act accordingly / bring own vpn services up or down. Which in end allows to access the offsite server without the need of continous exposure of the Wireguard service. 

