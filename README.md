# action_of_java
xdv in java implementation 


## create ssh key and config git
### such as name and email 

git config --global user.name "gaoyong"
git config --global user.email "gaoyong@wucar.com.cn"

### create ssh key

ssh-keygen  -t rsa -C "gaoyong@wucar.com.cn"
Enter file in which to save the key (/Users/gaoyong/.ssh/id_rsa): ./id_rsa_of_github_action_of_java
Enter passphrase (empty for no passphrase): action_of_java

Enter same passphrase again: action_of_java

Your identification has been saved in ./id_rsa_of_github_action_of_java.

Your public key has been saved in ./id_rsa_of_github_action_of_java.pub.

The key fingerprint is:

SHA256:FrqtIe723Y39pIENSIv65iem+IKYhuuc0BsI5YO6vkU gaoyong@wucar.com.cn

The key's randomart image is:


### set the key on github

### test 

ssh -i id_rsa_of_github_action_of_java -T git@github.com

