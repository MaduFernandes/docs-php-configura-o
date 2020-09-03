# 📎 PHP 

## Download de diferentes versões do **PHP** .

Faça o download do seguinte pacote:
```
sudo apt install software-properties-common
```
Em seguida adicione o repositório:
```
sudo add-apt-repository ppa:ondrej/php
```
Atualize os pacotes:
```
sudo apt update
```
Depois disso, podemos instalar a versão que desejamos do **PHP**
```
sudo apt install php{versão}
```

## Alterar a versão do PHP

Veja quais são as versões que tem instalada na sua máquina:
```
sudo update-alternatives --config php
```
O retorno vai ser parecido com isso:
```shell
Existem 2 escolhas para a alternativa php (disponibiliza /usr/bin/php).

  Selecção   Caminho          Prioridade Estado
------------------------------------------------------------
* 0            /usr/bin/php7.4   74        modo automático
  1            /usr/bin/php7.2   72        modo manual
  2            /usr/bin/php7.4   74        modo manual

Pressione <enter> para manter a escolha actual[*], ou digite o número da selecção: 

```
Escolha a versão que deseja usar e pressione [Enter].

Para confirmar a troca da versão, no terminal use o comando:
```shell
php -v
```