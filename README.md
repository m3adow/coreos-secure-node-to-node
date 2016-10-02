# Securing CoreOS node to node communication
This repo is intended for evaluating different methods of secure node to node communication for CoreOS. As Flannel doesn't provide this
WIP Master template(s) for CoreOS to enable secure node to node communication.

Templates can be used with my [cloud-config-creator](https://github.com/m3adow/cloud-config-creator) creator. The **out/** subdir of every method should contain example files.

Possible connection methods which  

Overlay Network agnostic methods:

* [tinc](https://tinc-vpn.org/)
* [IPOP](http://ipop-project.org/)
* [PeerVPN](https://peervpn.net/)
* [FreeLAN](https://www.freelan.org/)
* [Open vSwitch](http://openvswitch.org/)

Overlay Networks:

* [Weave](https://www.weave.works/docs/net/latest/features/#security)
