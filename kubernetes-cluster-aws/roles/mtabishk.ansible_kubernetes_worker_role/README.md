Ansible Role: ansible-kubernetes-worker-role
=========

Ansible Role for configuring K8s worker node.

Requirements
------------ 
Check out the README.md file of this repository
https://github.com/mtabishk/ansible-kubernetes-cluster-aws


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
 - name: use the k8s master role
   hosts: tag_name_master
   roles:
      - mtabishk.ansible_kubernetes_worker_role
```

License
-------

BSD
