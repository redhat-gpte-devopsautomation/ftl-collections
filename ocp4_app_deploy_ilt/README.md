# Ansible Collection - redhat_gpe.ocp4_app_deploy_ilt

```bash
eval $(
echo "export GUID=c3po"
echo "export OCP_APPS_DOMAIN=apps.cluster-XXXXX.XXXXX.sandboxXXXX.opentlc.com"
echo "export OCP_API=https://api.cluster-XXXXX.XXXXX.sandboxXXXX.opentlc.com:6443"
echo "export OCP_PASSWORD=secret"
)
```
```bash
ansible-playbook playbooks/main.yml -e ocp_user=user1 --tags solve_lab_01
ansible-playbook playbooks/main.yml -e ocp_user=user1 --tags grade_lab_01
ansible-playbook playbooks/main.yml -e ocp_user=user1 --tags reset_lab_01
ansible-playbook playbooks/main.yml -e ocp_user=user1 --tags solve_all
ansible-playbook playbooks/main.yml -e ocp_user=user1 --tags grade_all
ansible-playbook playbooks/main.yml -e ocp_user=user1 --tags reset_all
```
```
ansible-galaxy collection install git+https://github.com/redhat-gpte-devopsautomation/ftl-collections.git -p /usr/share/ansible/collections/ansible_collections
```
