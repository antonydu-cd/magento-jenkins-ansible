## 启动 Jenkins + Ansible
/usr/local/bin/docker-compose up

## 在Jenkins安装 gitlab 插件

## shell
docker exec -e ANSIBLE_STDOUT_CALLBACK=debug ansible ansible-playbook -i /etc/playbook/project/hosts /etc/playbook/project/deploy.yml -v