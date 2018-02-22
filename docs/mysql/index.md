#Instalação do MySQL 5.7 para Windows



Este *manual* descreve como instalar o MySQL Community Server 5.7 para Windows 10 (32/64 bits) . O procedimento é semelhante para Windows 7, 8.0 e 8.1 (32 e 64 bits).

Favor seguir este procedimento de instalação para facilitar o acompanhamento das aulas de Banco de Dados na Universidade São Judas Tadeu (USJT)



Clique nas imagens para aumentá-las (*zoom in* - fazer um zoom). 

**1)** Acesse o endereço do site do banco de dados MySQL: http://www.mysql.com/.

Clique no item de menu "Downloads". 

[![img](https://4.bp.blogspot.com/-x8VLY4yYD8M/WaOBn1v1IXI/AAAAAAAABbo/UH7wJpak6gUhwFYr_wxoCqjU-arFODbfgCLcBGAs/s640/2017-08-27%2B23_29_53-MySQL.png)](https://4.bp.blogspot.com/-x8VLY4yYD8M/WaOBn1v1IXI/AAAAAAAABbo/UH7wJpak6gUhwFYr_wxoCqjU-arFODbfgCLcBGAs/s1600/2017-08-27%2B23_29_53-MySQL.png)


**2)** Na página "Downloads", vá até o fim da página e clique no link  "Community (GPL) Downloads »"

[![img](https://4.bp.blogspot.com/-7RM7KV_u12s/WaOBnaFMSMI/AAAAAAAABbg/gmrTGkqlnc0yfj2sKlwSrwdfwqcfTEARACLcBGAs/s640/2017-08-27%2B23_32_19-MySQL%2B__%2BMySQL%2BDownloads.png)](https://4.bp.blogspot.com/-7RM7KV_u12s/WaOBnaFMSMI/AAAAAAAABbg/gmrTGkqlnc0yfj2sKlwSrwdfwqcfTEARACLcBGAs/s1600/2017-08-27%2B23_32_19-MySQL%2B__%2BMySQL%2BDownloads.png)


**3)** Na página "MySQL Community Downloads",  clique no link "MySQL Community Server (GPL)". A versão deste manual de instalação é 5.7.19 (acessado em 27 de agosto de 2017).

[![img](https://2.bp.blogspot.com/-1qtJMag0-Kw/WaOBoFZm54I/AAAAAAAABbs/Jg8jDhs5ICk6ZJ6awUL9kj5ks5-GbC-3gCLcBGAs/s640/2017-08-27%2B23_32_39-MySQL%2B__%2BMySQL%2BCommunity%2BDownloads.png)](https://2.bp.blogspot.com/-1qtJMag0-Kw/WaOBoFZm54I/AAAAAAAABbs/Jg8jDhs5ICk6ZJ6awUL9kj5ks5-GbC-3gCLcBGAs/s1600/2017-08-27%2B23_32_39-MySQL%2B__%2BMySQL%2BCommunity%2BDownloads.png)



**4)** Na página "Download MySQL Community Server", vá até o final da página. 

[![img](https://3.bp.blogspot.com/-t-N7sYGtGTA/WaOBo4BU9NI/AAAAAAAABcM/4GBGBcr5P-E_tvQwL_sA8Q2n9_aI-PqhgCEwYBhgL/s640/2017-08-27%2B23_33_17-MySQL%2B__%2BDownload%2BMySQL%2BCommunity%2BServer.png)](https://3.bp.blogspot.com/-t-N7sYGtGTA/WaOBo4BU9NI/AAAAAAAABcM/4GBGBcr5P-E_tvQwL_sA8Q2n9_aI-PqhgCEwYBhgL/s1600/2017-08-27%2B23_33_17-MySQL%2B__%2BDownload%2BMySQL%2BCommunity%2BServer.png)


**5)** Verifique se a opção "Select Operationg System" está como "Microsoft Windows" .

Clique no link "Go to Download Page >" do item "Windows (x86, 32 & 64 bit), MySQL Installer MSI".

[![img](https://3.bp.blogspot.com/-_Wv-1rZCxWk/WaOHYsYAaWI/AAAAAAAABcY/m1Tf_IBLpTE1x48QaUmhO7vLcJRAzATxQCLcBGAs/s640/2017-08-28%2B00_00_27-MySQL%2B__%2BDownload%2BMySQL%2BCommunity%2BServer.png)](https://3.bp.blogspot.com/-_Wv-1rZCxWk/WaOHYsYAaWI/AAAAAAAABcY/m1Tf_IBLpTE1x48QaUmhO7vLcJRAzATxQCLcBGAs/s1600/2017-08-28%2B00_00_27-MySQL%2B__%2BDownload%2BMySQL%2BCommunity%2BServer.png)


**6)** Na página "Download MySQL Installer", perceba que o instalador é de 32 bits, porém, ele instalará tanto MySQL de 32 bits como de 64 bits.

[![img](https://4.bp.blogspot.com/-iyFKcuOw8Cc/WaOKxSrWgJI/AAAAAAAABco/Jb3UnIAosIMjV3s2gsKC-IEfxMTRYipEACLcBGAs/s640/2017-08-28%2B00_13_29-MySQL%2B__%2BDownload%2BMySQL%2BInstaller.png)](https://4.bp.blogspot.com/-iyFKcuOw8Cc/WaOKxSrWgJI/AAAAAAAABco/Jb3UnIAosIMjV3s2gsKC-IEfxMTRYipEACLcBGAs/s1600/2017-08-28%2B00_13_29-MySQL%2B__%2BDownload%2BMySQL%2BInstaller.png)


**7)**  No final dessa página, irá aparecer dois botões de download para "Windows (x86, 32 bit), MSI Installer". Um é menor com 18,5 MB e outro possui 378,8 MB.

O instalador menor é para computadores que têm acesso direto à Internet e sem serviço de Proxy, onde o usuário pode escolher quais itens deseja fazer download e instalá-los na hora - também conhecido como instalação online.

O instalador maior, também conhecido como instalador offline, é para computadores que não possuem acesso à Internet ou que não conseguem acessar a partir de um serviço de Proxy. Perceba que todos os itens do servidor MySQL já estão disponíveis neste instalador.  Esta é a melhor opção para a maioria dos usuários, por isso, vamos fazer download do instalador maior. 

[![img](https://2.bp.blogspot.com/-X4NDLFMH5TU/WaOKxadJQYI/AAAAAAAABck/NBKqfkc9IJkvKpr4oUZ8Up9_4fuEr_ekwCLcBGAs/s640/2017-08-28%2B00_13_39-MySQL%2B__%2BDownload%2BMySQL%2BInstaller.png)](https://2.bp.blogspot.com/-X4NDLFMH5TU/WaOKxadJQYI/AAAAAAAABck/NBKqfkc9IJkvKpr4oUZ8Up9_4fuEr_ekwCLcBGAs/s1600/2017-08-28%2B00_13_39-MySQL%2B__%2BDownload%2BMySQL%2BInstaller.png)


**8)** Na página "Begin Your Download", irá aparecer dois botões pedindo para se logar ("Login »") ou se cadastrar ("Sign Up »"). Em vez disso, clique no link "No thanks, just start my download." ("Não, obrigado, apenas inicie o meu download.") que aparece mais abaixo. 

[![img](https://2.bp.blogspot.com/-UVXIHiElm1I/WaOBpvfUaOI/AAAAAAAABcA/VhiXcAZlmBgOT2vv1_-8cYlW8DU3ZF6RwCLcBGAs/s640/2017-08-27%2B23_33_49-MySQL%2B__%2BBegin%2BYour%2BDownload.png)](https://2.bp.blogspot.com/-UVXIHiElm1I/WaOBpvfUaOI/AAAAAAAABcA/VhiXcAZlmBgOT2vv1_-8cYlW8DU3ZF6RwCLcBGAs/s1600/2017-08-27%2B23_33_49-MySQL%2B__%2BBegin%2BYour%2BDownload.png)

[![img](https://4.bp.blogspot.com/-VGeKyQB0WcE/WaOBqBPJKkI/AAAAAAAABcE/1gQdLa5ZBd8yRn8ds6Fx55Y-mD-khsnnQCLcBGAs/s640/2017-08-27%2B23_34_00-MySQL%2B__%2BBegin%2BYour%2BDownload.png)](https://4.bp.blogspot.com/-VGeKyQB0WcE/WaOBqBPJKkI/AAAAAAAABcE/1gQdLa5ZBd8yRn8ds6Fx55Y-mD-khsnnQCLcBGAs/s1600/2017-08-27%2B23_34_00-MySQL%2B__%2BBegin%2BYour%2BDownload.png)


**9)** A partir deste momento, o seu navegador irá começar a fazer o download do instalador do MySQL Community Server.

[![img](https://1.bp.blogspot.com/-9LpJigG93YA/WaOBqSREliI/AAAAAAAABcI/aUUZKXAv8pks2UN4_xP_2C2Shwvf2OV5QCLcBGAs/s640/2017-08-27%2B23_34_37-MySQL%2B__%2BBegin%2BYour%2BDownload.png)](https://1.bp.blogspot.com/-9LpJigG93YA/WaOBqSREliI/AAAAAAAABcI/aUUZKXAv8pks2UN4_xP_2C2Shwvf2OV5QCLcBGAs/s1600/2017-08-27%2B23_34_37-MySQL%2B__%2BBegin%2BYour%2BDownload.png)


**10)** Após fazer o download do executável, dê dois cliques nele para começar a instalação.

[![img](https://1.bp.blogspot.com/-TO3ffDYNfDs/WaOWPHSUptI/AAAAAAAABdA/71w53atLe1M8hyBs4s6N3Og371VxOhsIgCLcBGAs/s400/2017-08-18%2B16_32_07-MySQL%2BInstaller%2B-%2BCommunity.png)](https://1.bp.blogspot.com/-TO3ffDYNfDs/WaOWPHSUptI/AAAAAAAABdA/71w53atLe1M8hyBs4s6N3Og371VxOhsIgCLcBGAs/s1600/2017-08-18%2B16_32_07-MySQL%2BInstaller%2B-%2BCommunity.png)


**11)** Na tela de "License Agreement" ("Contrato de Licença"),  leia a licença do software e selecione a opção "I accept the license terms" ("Eu aceito os termos da licença") e pressione o botão "Next".

[![img](https://4.bp.blogspot.com/-mmPZPovwxZ0/WaOWQOIUbnI/AAAAAAAABdE/5NgkTrXjnt8w5RYQ3UmoXSUh4V6yMcfygCLcBGAs/s400/2017-08-18%2B16_33_23-MySQL%2BInstaller.png)](https://4.bp.blogspot.com/-mmPZPovwxZ0/WaOWQOIUbnI/AAAAAAAABdE/5NgkTrXjnt8w5RYQ3UmoXSUh4V6yMcfygCLcBGAs/s1600/2017-08-18%2B16_33_23-MySQL%2BInstaller.png)


**12)** Na tela "Choosing a Setup Type" ("Escolha um tipo de configuração"), irá aparecer 5 (cinco) tipos de configurações a serem instaladas:

a) *Developer Default* - escolha esta opção se o computador for usado para desenvolvimento de aplicativos com banco de dados MySQL. Será instalados o MySQL Server (SGBD), MySQL Shell, MySQL Router, MySQL WorkBench, MySQL for Excel, JDBC e ODBC para MySQL, componentes para Visual Studio,  entre outros itens de desenvolvimento.

[![img](https://4.bp.blogspot.com/-mg8IHH9KVmI/WaOWQbOYw5I/AAAAAAAABdI/kiNI9GdZMOkRgSn9AQsfIO3SMmkyOhKRgCLcBGAs/s400/2017-08-18%2B16_33_35-MySQL%2BInstaller.png)](https://4.bp.blogspot.com/-mg8IHH9KVmI/WaOWQbOYw5I/AAAAAAAABdI/kiNI9GdZMOkRgSn9AQsfIO3SMmkyOhKRgCLcBGAs/s1600/2017-08-18%2B16_33_35-MySQL%2BInstaller.png)

b) *Server only* - escolha esta opção se o computador for um servidor dedicado para Banco de Dados MySQL. Esta opção instala somente o SGBD e os aplicativos servidores.

[![img](https://1.bp.blogspot.com/-KW0YFSyGETI/WaOWQuqy4nI/AAAAAAAABdM/T7r1SKFvoNQBKdqf5sD77zGtdX2JRX5fACLcBGAs/s400/2017-08-18%2B16_33_41-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-KW0YFSyGETI/WaOWQuqy4nI/AAAAAAAABdM/T7r1SKFvoNQBKdqf5sD77zGtdX2JRX5fACLcBGAs/s1600/2017-08-18%2B16_33_41-MySQL%2BInstaller.png)

c) *Client only* - escolha esta opção se o computador for uma máquina cliente de desenvolvimento, ou seja, deseja acessar um servidor MySQL remotamente. Itens como MySQL Shell, MySQL Router, MySQL Workbench, JDBC e ODBC para MySQL e componentes para Visual Studio serão instalados.

[![img](https://3.bp.blogspot.com/-B7UsJEuPh_M/WaOWQxQ8_nI/AAAAAAAABdQ/PCkOhyJjN4k2Yy9eiiZqhxSZv3Q4A6u-wCLcBGAs/s400/2017-08-18%2B16_33_45-MySQL%2BInstaller.png)](https://3.bp.blogspot.com/-B7UsJEuPh_M/WaOWQxQ8_nI/AAAAAAAABdQ/PCkOhyJjN4k2Yy9eiiZqhxSZv3Q4A6u-wCLcBGAs/s1600/2017-08-18%2B16_33_45-MySQL%2BInstaller.png)

d) *Full* - escolha esta opção se deseja instalar todos os itens do catálogo do MySQL: MySQL Server, MySQL Shell, MySQL Router, MySQL Workbench,  todos os componentes de conexão e desenvolvimento, além de toda a documentação.

[![img](https://3.bp.blogspot.com/-XW0mNN00WEs/WaOWRERqklI/AAAAAAAABdU/_vffvMt2X7ICdarZFPJMA_MC3rNrLmLGACLcBGAs/s400/2017-08-18%2B16_33_50-MySQL%2BInstaller.png)](https://3.bp.blogspot.com/-XW0mNN00WEs/WaOWRERqklI/AAAAAAAABdU/_vffvMt2X7ICdarZFPJMA_MC3rNrLmLGACLcBGAs/s1600/2017-08-18%2B16_33_50-MySQL%2BInstaller.png)

e) *Custom*  -  escolha esta opção se deseja personalizar a instalação, escolhendo somente os itens necessários. Se o seu computador for Windows 64 bits e deseja instalar algum item de 32 bits, selecione esta opção. 

[![img](https://2.bp.blogspot.com/-4r8vWH_yawM/WaOWRUqGbFI/AAAAAAAABdY/0Si4--7I5mwCv5_-swOo5KWbVnjNn6-iQCLcBGAs/s400/2017-08-18%2B16_33_54-MySQL%2BInstaller.png)](https://2.bp.blogspot.com/-4r8vWH_yawM/WaOWRUqGbFI/AAAAAAAABdY/0Si4--7I5mwCv5_-swOo5KWbVnjNn6-iQCLcBGAs/s1600/2017-08-18%2B16_33_54-MySQL%2BInstaller.png)


**13)**  Para a maioria dos desenvolvedores,  escolher a opção "Developer Default" parece ser a melhor opção. Porém, esta opção instalará vários itens que são desnecessários e que vão ocupar muito espaço no disco.

Neste exemplo, iremos escolher a opção "Custom" e selecionar somente os itens necessários: serão instalados somente o **MySQL Server**, **MySQL Workbench** e o **MySQL Shell**. 

Após isso, pressione o botão "Next".

[![img](https://3.bp.blogspot.com/-4r8vWH_yawM/WaOWRUqGbFI/AAAAAAAABfE/P58wycY-tPAoM-ZBm1pUEpRLfp7OTITxgCEwYBhgL/s400/2017-08-18%2B16_33_54-MySQL%2BInstaller.png)](https://3.bp.blogspot.com/-4r8vWH_yawM/WaOWRUqGbFI/AAAAAAAABfE/P58wycY-tPAoM-ZBm1pUEpRLfp7OTITxgCEwYBhgL/s1600/2017-08-18%2B16_33_54-MySQL%2BInstaller.png)


**14)** Na tela "Select Products and Features" ("Selecione produtos e recursos"), irá aparecer algumas categorias de produtos disponíveis:

- MySQL Servers
- Applications
- MySQL Connectors
- Documentation

[![img](https://3.bp.blogspot.com/-edd9WY53Svw/WaOWSYNVR7I/AAAAAAAABdo/9XeoRiW9EGgLd8Bu729dXe4QS31UExy4QCLcBGAs/s400/2017-08-18%2B17_07_53-MySQL%2BInstaller.png)](https://3.bp.blogspot.com/-edd9WY53Svw/WaOWSYNVR7I/AAAAAAAABdo/9XeoRiW9EGgLd8Bu729dXe4QS31UExy4QCLcBGAs/s1600/2017-08-18%2B17_07_53-MySQL%2BInstaller.png)


**15)** Escolher o MySQL Server.

Selecione a categoria "MySQL Servers" e clique no sinal + para expandir as subopções.



Escolha as opções MySQL Servers > MySQL Server > MySQL Server 5.7

Se for instalar em um ambiente de 64 bits, escolha o subitem **MySQL Server 5.7.19 - X64**.

Se for instalar em um ambiente de 32 bits, escolha o subitem **MySQL Server 5.7.19 - X86**.



[![img](https://1.bp.blogspot.com/-krTlFeM01zw/WaOWSm1DxRI/AAAAAAAABds/GzSynQSPgnkWkTC7PsSASGm3vVBWeVZpwCLcBGAs/s400/2017-08-18%2B17_08_02-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-krTlFeM01zw/WaOWSm1DxRI/AAAAAAAABds/GzSynQSPgnkWkTC7PsSASGm3vVBWeVZpwCLcBGAs/s1600/2017-08-18%2B17_08_02-MySQL%2BInstaller.png)

Clique  com o ponteiro do mouse na seta para a direita para selecionar o item para instalação.

[![img](https://4.bp.blogspot.com/-w6tZABLfLC8/WaOWS9f_Y7I/AAAAAAAABdw/JePxtESA9IMr9DA5AsELICv0yOIhvaKrgCLcBGAs/s400/2017-08-18%2B17_08_05-MySQL%2BInstaller.png)](https://4.bp.blogspot.com/-w6tZABLfLC8/WaOWS9f_Y7I/AAAAAAAABdw/JePxtESA9IMr9DA5AsELICv0yOIhvaKrgCLcBGAs/s1600/2017-08-18%2B17_08_05-MySQL%2BInstaller.png)


**16)** Escolher o MySQL Workbench.

Selecione a categoria "Applications" e clique no sinal + para expandir as subopções.

Escolha as opções Applications > MySQL Workbench > MySQL Workbench 6.3 > MySQL Workbench 6.3.9 - X64.

Clique  com o ponteiro do mouse na seta para a direita para selecionar o item para instalação.

[![img](https://1.bp.blogspot.com/-cnJOXr4whec/WaOWTBNVJkI/AAAAAAAABd0/_e1UY4N8mhAdwLiy6UzysSNjFkZIpklTgCLcBGAs/s400/2017-08-18%2B17_08_15-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-cnJOXr4whec/WaOWTBNVJkI/AAAAAAAABd0/_e1UY4N8mhAdwLiy6UzysSNjFkZIpklTgCLcBGAs/s1600/2017-08-18%2B17_08_15-MySQL%2BInstaller.png)


**17)** Escolher o MySQL Shell.

Selecione a categoria "Applications" e clique no sinal + para expandir as subopções.

Escolha as opções Applications > MySQL Shell > MySQL Shell 1.0 > MySQL Shell 1.0.9 - X64.

Clique  com o ponteiro do mouse na **seta para a direita** para selecionar o item para instalação.

Após isso, pressione o botão "Next". 

[![img](https://1.bp.blogspot.com/-qfeeVGiEwB4/WaOWTZb-3kI/AAAAAAAABd4/lw414CztHAUCVA_rdSifix4ALEel1DwoQCLcBGAs/s400/2017-08-18%2B17_09_23-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-qfeeVGiEwB4/WaOWTZb-3kI/AAAAAAAABd4/lw414CztHAUCVA_rdSifix4ALEel1DwoQCLcBGAs/s1600/2017-08-18%2B17_09_23-MySQL%2BInstaller.png)


**18)** Na tela "Installation" ("Instalação"), pressione o botão "Execute" ("Executar") para que  instalação se inicie. 

[![img](https://3.bp.blogspot.com/-DjKUKTba-pc/WaOWTQbetYI/AAAAAAAABd8/mKelAXd0IbEBjtwRmIl2LqV1QViM_uBxACLcBGAs/s400/2017-08-18%2B17_09_29-MySQL%2BInstaller.png)](https://3.bp.blogspot.com/-DjKUKTba-pc/WaOWTQbetYI/AAAAAAAABd8/mKelAXd0IbEBjtwRmIl2LqV1QViM_uBxACLcBGAs/s1600/2017-08-18%2B17_09_29-MySQL%2BInstaller.png)


**19)** A instalação poderá levar algum tempo dependendo da configuração do seu computador.

[![img](https://4.bp.blogspot.com/-yh1qBPadYk0/WaOWT3BRpqI/AAAAAAAABeA/79toRlquiGot8UhMV0sGTZqe4NmwRXmbwCLcBGAs/s400/2017-08-18%2B17_09_55-MySQL%2BInstaller.png)](https://4.bp.blogspot.com/-yh1qBPadYk0/WaOWT3BRpqI/AAAAAAAABeA/79toRlquiGot8UhMV0sGTZqe4NmwRXmbwCLcBGAs/s1600/2017-08-18%2B17_09_55-MySQL%2BInstaller.png)


**20)** Após a instalação estar completa, pressione o botão "Next".

[![img](https://3.bp.blogspot.com/--JuAZQPjqPI/WaOWT7_dlqI/AAAAAAAABeE/S6_fpMHatpsHxh3_ddZZ7AS04clpu-yugCLcBGAs/s400/2017-08-18%2B17_15_50-MySQL%2BInstaller.png)](https://3.bp.blogspot.com/--JuAZQPjqPI/WaOWT7_dlqI/AAAAAAAABeE/S6_fpMHatpsHxh3_ddZZ7AS04clpu-yugCLcBGAs/s1600/2017-08-18%2B17_15_50-MySQL%2BInstaller.png)


**21)** Na tela "Product Configuration" ("Configuração do Produto"), pressione o botão "Next".

[![img](https://4.bp.blogspot.com/-e2iDaSHVVO8/WaOWUPWz1xI/AAAAAAAABeI/CEEwyEbCqtQACVHTbH5JzkTMIpWhqd6JACLcBGAs/s400/2017-08-18%2B17_15_56-MySQL%2BInstaller.png)](https://4.bp.blogspot.com/-e2iDaSHVVO8/WaOWUPWz1xI/AAAAAAAABeI/CEEwyEbCqtQACVHTbH5JzkTMIpWhqd6JACLcBGAs/s1600/2017-08-18%2B17_15_56-MySQL%2BInstaller.png)


**22)** Na tela "Type and Networking" ("Tipo e Rede"), escolha a opção "Standalone MySQL Server / Classic MySQL Replication".  Em seguida, pressione o botão "Next".

[![img](https://2.bp.blogspot.com/-y-c3r-48SS4/WaOWUtCZ9pI/AAAAAAAABeM/QfUBUqlS3bc9uKor1Yr9gkas2uU0wSlKACLcBGAs/s400/2017-08-18%2B17_16_19-MySQL%2BInstaller.png)](https://2.bp.blogspot.com/-y-c3r-48SS4/WaOWUtCZ9pI/AAAAAAAABeM/QfUBUqlS3bc9uKor1Yr9gkas2uU0wSlKACLcBGAs/s1600/2017-08-18%2B17_16_19-MySQL%2BInstaller.png)


**23)** Na próxima tela, no item "Server Configuration Type" ("Tipo de Configuração do Servidor"), escolha o "Config Type" ("Tipo de Configuração") como "Development Machine" ("Máquina de desenvolvimento").

Em "Connectivity", ative a opção "TCP/IP" e verifique se o "Port Number" ("Número da Porta") está como 3306.

Caso necessite, libere a porta no firewall do Windows escolhendo a opção "Open Firewall port for network access". Desta forma, outros computadores da sua rede e da Internet poderão acessar o MySQL Server da sua máquina.

Em seguida, pressione o botão "Next".

[![img](https://4.bp.blogspot.com/-v0NnSPZyRPI/WaOWUyLcHWI/AAAAAAAABeQ/v55-fptXwJsQUj4W4eWPYe9Ohk6H1PeXACLcBGAs/s400/2017-08-18%2B17_16_23-MySQL%2BInstaller.png)](https://4.bp.blogspot.com/-v0NnSPZyRPI/WaOWUyLcHWI/AAAAAAAABeQ/v55-fptXwJsQUj4W4eWPYe9Ohk6H1PeXACLcBGAs/s1600/2017-08-18%2B17_16_23-MySQL%2BInstaller.png)


**24)** Na tela "Accounts and Roles" ("Contas e papéis/funções"), digite a senha do usuário "root" que é o administrador do banco de dados MySQL. Tente criar uma senha forte ("strong") que tenha letras maiúsculas, minúsculas, números e sinais de pontuação.

Caso queira, pode-se criar uma outra conta no banco de dados pressionando o botão "Add User" ("Adicionar Usuário").

Em seguida, pressione o botão "Next". 

[![img](https://2.bp.blogspot.com/-iDv7g4atW_I/WaOWVc7Hp_I/AAAAAAAABeY/ViKJMjLugqIK75qkn9WPXD6F6YaFN739gCLcBGAs/s400/2017-08-18%2B17_19_36-MySQL%2BInstaller.png)](https://2.bp.blogspot.com/-iDv7g4atW_I/WaOWVc7Hp_I/AAAAAAAABeY/ViKJMjLugqIK75qkn9WPXD6F6YaFN739gCLcBGAs/s1600/2017-08-18%2B17_19_36-MySQL%2BInstaller.png)


**25)** Na tela "Windows Service", selecione a opção "Configure MySQL Server as a Windows Service" ("Configure o MySQL Server como um serviço Windows")  para que o MySQL seja executado em background (segundo plano) como um serviço do Windows.

Na opção "Windows Service Name", escolha o nome que o serviço do MySQL Server terá no Windows. Por padrão, o nome será "MySQL57".

A opção "Start the MySQL Server at System Startup" fará que o serviço do MySQL seja iniciado todas as vezes que o Windows iniciar.  Para usuários que possuem computadores lentos  ou que não desejam ocupar a memória com o MySQL todas as vezes que o Windows iniciar, desativem esta opção.

No item "Run Windows Service as..." ("Execute o serviço do Windows como..."), mantenha selecionada a opção "Standard System Account" (usar o "System Account" do Windows).

Em seguida, pressione o botão "Next". 

[![img](https://1.bp.blogspot.com/-8gisIjvt9B0/WaOWVm3t5UI/AAAAAAAABeg/Qose7Jltxsczicj5y3NWiy9Z26ufsGqKACLcBGAs/s400/2017-08-18%2B17_22_18-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-8gisIjvt9B0/WaOWVm3t5UI/AAAAAAAABeg/Qose7Jltxsczicj5y3NWiy9Z26ufsGqKACLcBGAs/s1600/2017-08-18%2B17_22_18-MySQL%2BInstaller.png)


**26)** Na tela "Plugins and Extensions" ("Plugins e extensões"),  não selecione nada e pressione o botão "Next".

[![img](https://1.bp.blogspot.com/-sMvS5E53mmA/WaOWVx7UhMI/AAAAAAAABek/sfv69d7G08U0Yxc_CfK5x00qa7ojraSnQCLcBGAs/s400/2017-08-18%2B17_22_36-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-sMvS5E53mmA/WaOWVx7UhMI/AAAAAAAABek/sfv69d7G08U0Yxc_CfK5x00qa7ojraSnQCLcBGAs/s1600/2017-08-18%2B17_22_36-MySQL%2BInstaller.png)


**27)** Na tela "Apply Configuration" ("Aplicar configurações"), pressione o botão "Execute".

[![img](https://2.bp.blogspot.com/--magBPGlgHI/WaOWWZDMIYI/AAAAAAAABeo/HyMZA62HpDIuTH3OJY8LZ80shheGwW-JwCLcBGAs/s400/2017-08-18%2B17_22_43-MySQL%2BInstaller.png)](https://2.bp.blogspot.com/--magBPGlgHI/WaOWWZDMIYI/AAAAAAAABeo/HyMZA62HpDIuTH3OJY8LZ80shheGwW-JwCLcBGAs/s1600/2017-08-18%2B17_22_43-MySQL%2BInstaller.png)

[![img](https://2.bp.blogspot.com/-zZ-Mp4Q_O9I/WaOWXIDJnpI/AAAAAAAABes/b_iId6xmfb82_LMRAqkTNXxPKWS-3wmnACLcBGAs/s400/2017-08-18%2B17_22_51-MySQL%2BInstaller.png)](https://2.bp.blogspot.com/-zZ-Mp4Q_O9I/WaOWXIDJnpI/AAAAAAAABes/b_iId6xmfb82_LMRAqkTNXxPKWS-3wmnACLcBGAs/s1600/2017-08-18%2B17_22_51-MySQL%2BInstaller.png)


**28)** Após o instalador configurar o computador com o MySQL, pressione o botão "Finish".

[![img](https://1.bp.blogspot.com/-6H4V89QZSNo/WaOWXnLACKI/AAAAAAAABew/0HUtpoJCXVkd1rEbCIhc_Ie7jkclra7fACLcBGAs/s400/2017-08-18%2B17_23_04-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-6H4V89QZSNo/WaOWXnLACKI/AAAAAAAABew/0HUtpoJCXVkd1rEbCIhc_Ie7jkclra7fACLcBGAs/s1600/2017-08-18%2B17_23_04-MySQL%2BInstaller.png)


**29)** Na tela "Product Configuration", pressione o botão "Next".

[![img](https://1.bp.blogspot.com/-i7O4pQp8658/WaOWZENDcMI/AAAAAAAABe8/PJH4JhzAAYIaJz-c0-VqAVr8JKrqbLgeACLcBGAs/s400/2017-08-18%2B17_23_27-MySQL%2BInstaller.png)](https://1.bp.blogspot.com/-i7O4pQp8658/WaOWZENDcMI/AAAAAAAABe8/PJH4JhzAAYIaJz-c0-VqAVr8JKrqbLgeACLcBGAs/s1600/2017-08-18%2B17_23_27-MySQL%2BInstaller.png)


**30)** Na tela "Installation Complete" ("Instalação Completa"), selecione os itens que deseja iniciar após a instalação:

- Start MySQL Workbench after Setup ("Iniciar MySQL Workbench")
- Start MySQL Shell after Setup ("Iniciar MySQL Shell")

Para encerrar a instalação, pressione o botão "Finish".

[![img](https://2.bp.blogspot.com/-7GbuE5eSkyU/WaOWZrycr3I/AAAAAAAABfA/cdDaq1HPQf4sCf4l_YDxHcpq5S2ShiiwwCLcBGAs/s400/2017-08-18%2B17_23_33-MySQL%2BInstaller.png)](https://2.bp.blogspot.com/-7GbuE5eSkyU/WaOWZrycr3I/AAAAAAAABfA/cdDaq1HPQf4sCf4l_YDxHcpq5S2ShiiwwCLcBGAs/s1600/2017-08-18%2B17_23_33-MySQL%2BInstaller.png)