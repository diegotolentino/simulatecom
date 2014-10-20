Sobre
============

Utiliza o software <a href="http://www.dest-unreach.org/socat/">socat</a> para a existência de uma porta COM com uma balança 9091 da fabricante Toledo.

Com a facilidade de se utilizar um arquivo contendo os pesos separados linha-a-linha, este script reduz em muito os custos de testes de pesagem.

Instalação
-------------

Assumindo que o python e o pip estão instalados.

# pacotes python utilizados
pip install pyserial pyyaml

# pacotes debian utilizados
aptitude install socat


Utilização
-------------

	$ python playlog test.cap

