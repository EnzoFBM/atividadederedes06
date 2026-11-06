comandos sequenciais do Cisco IOS necessários para a execução e validação da configuração das vlans:
0 - (senha)
1 - enable
1.5 - (segunda senha)
2 - configure terminal
3 - vlan 10
4 - name alunos
exit
5 - vlan 20
6 - name visitantes
exit
7 - interface fastethernet 0/1
8 - switchport mode access
9 - switchport access vlan 20
exit
7 - interface fastethernet 1/1
8 - switchport mode access
9 - switchport access vlan 10
aí é só fazer isso em todos os switches de borda :) os pcs e os laptops só irão poder comunicar entre outros na mesma vlan dps de configurar as portas trunk entre os switchs
