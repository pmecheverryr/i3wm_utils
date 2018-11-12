# i3wm Monitors 
Scripts que nos permite utilizar otro monitor exteno

#Requisito
betterlockscreen

##Adicionar la siguiente linea en .config/i3/config

echo "exec --no-startup-id sh ~/i3wm_utils/monitor/monitors.sh" >> ~/.config/i3/config
