# mern-stack-example
Example Project on how to create MERN Stack


# mern-stack-example
Example Project on how to create MERN Stack



install kubectl
-----------------
curl -O https://s3.us-west-2.amazonaws.com/amazon-eks/1.24.11/2023-03-17/bin/linux/amd64/kubectl

chmod +x ./kubectl

sudo cp ./kubectl /usr/local/bin

export PATH=/usr/local/bin:$PATH


install awscli
--------------

curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"

unzip awscliv2.zip

sudo ./aws/install


set aws context
---------------
aws eks update-kubeconfig --name EKS_CLUSTER_NAME --region us-west-2ggg
