# Instalar todo en linux
> Este es un listado de comandos para la instalación de Librerías, frameworks, programas y todo lo necesario para el entorno de un programador.

## Instalación de [_【 GOOGLE CHROME 】_](https://www.google.com/intl/es-419/chrome/)
```sh
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
sudo apt-get -f install
```

## Instalación de [_【 NodeJs 】_](https://nodejs.org)

```sh
sudo apt-get install curl python-software-properties
curl -sL https://deb.nodesource.com/setup_10.x | sudo bash -
sudo apt-get install -y nodejs
```


## Instalación de [_【 IONIC + CORDOVA 】_](https://ionicframework.com/)
```sh
sudo npm i -g ionic@latest
sudo npm i -g cordova
```

## Instalación de [_【 React Native CLI 】_](https://facebook.github.io/react-native/)
```sh
sudo npm i -g react-native-cli
```

## Instalación de [_【 EXPO CLI 】_](https://docs.expo.io/versions/latest/)
```sh
sudo npm i -g expo-cli
```

## Instalación de [_【 LAMP 】_]()
```sh
sudo apt-get update
sudo apt-get install apache2
sudo ufw enable
sudo apt-get install mysql-server
sudo mysql_secure_installation
sudo apt-get install php libapache2-mod-php php-mysql
sudo service apache2 restart
sudo chown -R $USER:root /var/www/
sudo apt-get install phpmyadmin

sudo nano /etc/apache2/apache2.conf
#Agregar la siguiente línea: 
Include /etc/phpmyadmin/apache.conf
```

```sh
#Setear el usuario root al phpmyadmin
sudo mysql -u root -p
use mysql

update user set authentication_string=PASSWORD("your_password") where user = 'root';
update user set plugin='mysql_native_password' where user = 'root';
flush privileges;
```

## Instalación de [_【 COMPOSER + LARAVEL 】_](https://laravel.com)
```sh
sudo apt install composer -y
sudo apt-get install php7.2-zip
composer global require laravel/installer
```

## Instalación de [_【  】_]()
```sh
```

## EQUIPO [_NoEMEC_](https://www.noemec.com)
<img src="https://www.noemec.com/members.svg">