Hi There!

For deploying the application go to the k8s-yaml folder and run the app.yaml in the cluster 'a'.
redis.yaml in the cluster 'b'. 


For kubespray you can get it from the original git hub link:
git clone https://github.com/kubernetes-sigs/kubespray.git

after once you cloned the content replace the inventory.ini at kubespary/inventory/sample/ 
and then change the network plugin details in the k8s-cluster.yaml from calico to weave and then you can run the ansible playbook.


for a cluster I've used the below link to create the cluster
https://www.howtoforge.com/setup-a-kubernetes-cluster-on-aws-ec2-instance-ubuntu-using-kubeadm/

