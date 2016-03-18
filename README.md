# Agenda em Python
Simples projeto de agenda de telefone e e-mail em python, simples e pratica.

#compilar .exe
Caso queira compilar a mesma em .exe para distribuição, utilize o py2exe.

crie um arquivo setup.py
(from distutils.core import setup
import py2exe)

setup(console=['agenda.py'])
obs: os dois arquivos devem estar na mesma pasta, após feito isso, abra o cmd do windows e digite (python setup.py py2exe)
