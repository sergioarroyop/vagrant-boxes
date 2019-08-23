# vagrant-boxes

Para crear un nuevo entorno símplemente tienes que cambiar las siguiente variables:

File: ansible-init/inventory/group-vars/vagrant

```
# Ionic
proyect_name: Pollito
proyect_template: tabs #my-first-app #blank #tabs #sidemenu #conference
```

Una vez cambiadas las variables desde la carpeta debian9 símplemente hay que lanzar

```vagrant up```

Cuando haya acabado la ejecución tu aplicación estará lista a través de la siguiente url

```http://192.168.222.222:8100```