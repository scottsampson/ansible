  apt-get install -y software-properties-common
  apt-add-repository ppa:ansible/ansible
  apt-get update && apt-get upgrade -y
  apt-get install -y ansible
  cd /etc && rm -rf /etc/ansible 
  git clone https://github.com/nowthatsamatt/ansible.git
