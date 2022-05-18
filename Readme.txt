Установить "ubuntu.ova"

пароль для входа в система: root1234

########################################
	вход в pgadmin4
http://<ip-address-ubuntu>/pgadmin4

login: bmaks349@gmail.com
password: 110315


########################################
		Изменить параметры Файрвола
	Доступ для ip
sudo ufw allow from <ip_физической_машинны>

	Удаление правила по его номеру
sudo ufw status numbered
sudo ufw delete [number]

	Проверка состояния UFW 
sudo ufw status verbose

	


