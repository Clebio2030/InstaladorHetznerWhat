# Instalador Whaticket SaaS - Redis em Docker

Neste instalador o pm2 é no usuário root.

* Atualização pelo terminal parece não funcionar.

```bash
sudo apt -y update && apt -y upgrade
```

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/Clebio2030/InstaladorHetznerWhat InstaladorHetznerWhat && sudo chmod -R 777 InstaladorHetznerWhat  && cd InstaladorHetznerWhat  && sudo ./install_primaria
```

## Requisitos

| --- | Mínimo | Recomendado |
| --- | --- | --- |
| Node JS | 20.x | 20.x |
| Ubuntu | 20.x | 20.x |
| Memória RAM | 4Gb | 8Gb |  
