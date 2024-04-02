# TCC_ENG_SOFT_2024
Software Coletor De Dados 
Este software roda em platformIO/ dentro do VScode versões acima de 2018.
Para executar o código em Hardware vc precisará de: (Um cabo USB, impressora, uma placa de prototipagem (Mega2560), uma placa de rede (W5500). uma conexão com seu modem física, com cabo de par transado e um pluge (RJ45).
Configurarção, no campo IP(192.168.xx.xx), entre no seu computador no campo pesquisa (Search), com o comando (CMD), vai aparecer uma tela do prompot de comandos, digite (IPconfig/all), vai aparecer uma linha com o endereço do (DHCP SERVER: 192.168.XX.XX) anote que esse IP, refere-se ao seu modem. 
Com o endereço do modem digite no browser, de preferencia (Microsoft Edge), logo retornará a tela inicial de seu modem, agora digite a senha para acessa-lo, que encontra-se logo abaixo dele em uma etiqueta.
Após acessa-lo procure, os campos reservas de (IP) configurar o (MAC e IP) fixo, fora da faixa do DHCP.
teste a conexão com o cabo conectado, e a sua placa alimentada com tensão, ou simplesmente conectado com cabo USB. (A corrente é abaixo dos 500mA. Suporta tranquilamente).
Com o comando do endereço do (IP) que você fixou no seu modem e reprogramado no código do projeto (S.C.D.D) verifique o retorno. se retornar com os caracteres você obteve sucesso na instalação.
Altere as entradas ou os valores aritméticos conforme sua necessidade.
Pericles Silva
