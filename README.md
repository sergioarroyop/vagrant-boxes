# vagrant-boxes

Para clonar el repo junto a los submódulos debemos de clonar el repo con el siguiente comando

```git clone -b master --recursive https://github.com/sergioarroyop/vagrant-boxes.git```

# Standalone Box

Desde la carpeta debian9/debian9_standalone podemos ejecutar ```vagrant up``` para arrancar nuestro entorno

# IONIC Box

Para crear un nuevo entorno símplemente tienes que cambiar las siguiente variables:

File: ansible-init/inventory/group-vars/vagrant

```
# Ionic
proyect_name: Pollito
proyect_template: tabs #my-first-app #blank #tabs #sidemenu #conference
```

Una vez cambiadas las variables desde la carpeta debian9/debian9_ionic/ símplemente hay que lanzar

```vagrant up```

Cuando haya acabado la ejecución tu aplicación estará lista a través de la siguiente url

```http://192.168.222.222:8100```
