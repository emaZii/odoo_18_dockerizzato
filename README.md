### Odoo 18 Dockerizzato
Opzione A: Usare odoo-bin con shell (Consigliata)
Invece di far partire un intero server, entra nel container e lancia il comando di inizializzazione dicendo a Odoo di chiudersi subito dopo aver finito (--stop-after-init):
docker exec -it odoo18_app odoo -d lab18 -i base --stop-after-init
