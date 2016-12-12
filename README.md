# cisco-nxos-ansible-vxlan-evpn
Ansible playbooks to configure MP-BGP EVPN VXLAN using IP Unnumbered with OSPF and PIM SM in the Underlay and iBGP EVPN as the control plane. Spines act as route-reflectors and PIM Anycast RPs.

Option 1:

git clone https://github.com/mtarking/cisco-nxos-ansible-vxlan-evpn

Option 2:

Using the Dockerfile:

docker build -t cisco-nxos-ansible-vxlan-evpn .

docker run -it cisco-nxos-ansible-vxlan-evpn
