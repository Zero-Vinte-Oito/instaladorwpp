## Deploy Ubuntu 20.x

Configurando Servidor

```bash
sudo adduser deploy
```

```bash
sudo usermod -aG sudo deploy
```

```bash
sudo passwd root
```

```bash
su root
```

```bash
sudo apt update && sudo apt upgrade
```

## Instalação

FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/Zero-Vinte-Oito/instaladorwpp.git && sudo chmod -R 777 instaladorwpp && cd instaladorwpp && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd && rm -rf instaladorwpp && git clone https://github.com/Zero-Vinte-Oito/instaladorwpp.git && sudo chmod -R 777 instaladorwpp && cd instaladorwpp && sudo ./install_instancia
```

## Pós

Atualize o servidor.
```bash
sudo apt update && sudo apt upgrade
```


Caso a instancia não rode, deve ser atualizado a instancia.