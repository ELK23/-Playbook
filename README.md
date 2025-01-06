
- [Плейбук установки кликхаус, лайтхаус и вектор](#start)
  - [Требования](#prerequisite)
  - [Конфигурация](#configure)
  - [Инсталяция](#install)
 
## start

[https://github.com/ELK23/08-ansible-02-playbook/releases/tag/08-ansible-02-playbook](https://github.com/ELK23/08-ansible-02-playbook/releases/tag/08-ansible-03-yandex)

### prerequisite

rockylinux9.5
ansible

### configure

В `inventory/prod.yml` указать пользователя айпи и ссейч ключ.
В `template/vector.toml.j2` указать поместить конфигурацию вектор.

### install

ansible-playbook site.yml -i inventory/prod.yml -kK



