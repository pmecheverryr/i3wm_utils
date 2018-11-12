# i3wm Background_day
Scripts que nos permite cambiar imagen del dia de proveedores como National Geographics

#Requisito:
feh

##Adicionar la siguiente linea en .config/i3/config

echo "exec --no-startup-id sh ~/i3wm_utils/background_day/main.sh" >> ~/.config/i3/config
