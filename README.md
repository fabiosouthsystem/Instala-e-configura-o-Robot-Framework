Instalando o Robot Framework (Windows)

<div align="center">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r1.webp">
</p>

O Robot Framework é multi-plataforma, mas nesse tutorial direi o passo-a-passo para instalá-lo no Windows, então bora instalar o Robot Framework??? Irei mostrar o jeito mais tranquilo de fazer, existem outras formas, mas hoje vamos por esta!

<ul>
  <li>01 — Instalando o Python e pip [Pré-Requisitos]
Baixe o Python 2.7.x [https://www.python.org/downloads/] OBS.: Podem ocorrer problemas de compatibilidade com o Python 3.0, então recomendam o 2.7 por enquanto.
Instale via executável o Python 2.7. OBS.: Defina a variável de ambiente durante a instalação (recomendado).
</ul>

<div align="center">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r2.webp">
  
Se mesmo após a instalação não configurou as variáveis de ambiente, manualmente edite as variáveis e adicione “C:\Python27\;C:\Python27\Scripts”.

<div align="center">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r3.webp">
  
Para conferir se deu certo, no prompt de comando (cmd) execute:

python --version
pip -- version
  
<div align="center">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r4.webp">

<ul>
  <li>02 — Instalando o Robot Framework
    

  No prompt de comando (cmd) execute e aguarde a instalação:
  pip install robotframework
  Para saber se deu tudo certo no prompt de comando (cmd) execute:
  robot --version
</ul>
