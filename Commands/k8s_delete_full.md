sudo kubeadm reset
sudo rm -rf /etc/cni /etc/kubernetes /var/lib/dockershim /var/lib/etcd /var/lib/kubelet /var/run/kubernetes ~/.kube/*
sudo apt-get purge kubeadm kubectl kubelet kubernetes-cni kube*
sudo systemctl restart docker
sudo apt-get autoremove
sudo reboot
