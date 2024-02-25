Etapas de ajustes do projeto


Abra o terminal e vá até a pasta do projeto, no meu caso:

: ~$  cd Desktop/

:~/Desktop$ cd intro-pyspark/


Já dentro da pasta e ainda no terminal, execute os seguintes comandos:

:~/Desktop/intro-pyspark$ poetry new my-project
# utilizaremos o “poetry” para criar uma nova pasta chamada “my-project”


E agora, entre na nova pasta:

:~/Desktop/intro-pyspark/new my-project$


Dentro da pasta instale o “pyspark” com o seguinte comando

OBS.: antes da etapa de instalação, execute o comado para saber a versão do “pyspark” instalado na sua máquina. Pra assim instalar a versão compátivel  com o seu SO.

:~/Desktop/intro-pyspark/new my-project$ pyspark –version

No meu SO a versão é 3.2.4


Agora vamos instalar o “pyspark”

:~/Desktop/intro-pyspark/new my-project$ poetry add pyspark==3.2.4


Adicionar o “jupyter lab”

:~/Desktop/intro-pyspark/new my-project$ poetry add jupyterlab


Vamos iniciar o “shell” com o “poetry”

:~/Desktop/intro-pyspark/new my-project$ poetry shell


Pra finalizar, vamos inicializar o “jupyter lab”

:~/Desktop/intro-pyspark/new my-project$ jupyter-lab