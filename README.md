Instalando o Robot Framework (Windows)

<div align="left">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r0.png">
</p>
Robot Framework é uma estrutura de automação de teste de código aberto. Foi inicialmente desenvolvido pela Nokia Networks, no entanto, agora é mantido pela Robot Framework Foundation.

O Robot Framework é multi-plataforma, mas nesse tutorial direi o passo-a-passo para instalá-lo no Windows, então bora instalar o Robot Framework??? Irei mostrar o jeito mais tranquilo de fazer, existem outras formas, mas hoje vamos por esta!

<br/>

### ---- Pré-Requisitos Robot com Selenium Library ----
- Sistema Operacional Windows
- Download da Linguagem Python (https://www.python.org/downloads/)
- Marcar opção de instalar o PIP durante instalação do Python
- python --version
- pip --version
- Download do Robot Framework via linha de comando no terminal: pip install robotframework
- robot --version
- Download do Selenium Library: pip install robotframework-seleniumlibrary
- Download do Geckodriver: https://github.com/mozilla/geckodriver/releases
- Download do chrome driver (https://chromedriver.chromium.org/downloads)
- Salvar ambos os arquivos executáveis (geckodriver e chrome driver), dentro da pasta scripts onde foi instalado o Python na sua máquina.

<br/>


— Instalando o Python e pip [Pré-Requisitos]
Baixe o Python 2.7.x [https://www.python.org/downloads/] 
— OBS.: Podem ocorrer problemas de compatibilidade com o Python 3.0, então recomendam o 2.7 por enquanto.
— Instale via executável o Python 2.7. 
— OBS.: Defina a variável de ambiente durante a instalação (recomendado).


<div align="left">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r2.png">
  
Se mesmo após a instalação não configurou as variáveis de ambiente sozinho, você pode manualmente editar as variáveis e adicioná-las "C:\caminho_do_python_na_sua_maquina\;C:\caminho_do_python_na_sua_maquina\Scripts".

Exemplo: 

<div align="left">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r3.png">
  
Para conferir se deu certo, no prompt de comando (cmd) execute:

python --version
pip -- version
  
<div align="left">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r4.png">

<ul>
    <li>02 — Instalando o Robot Framework   
  - No prompt de comando (cmd) execute:
      
pip install -U robotframework
      
  E pronto!! Para saber se deu tudo certo no prompt de comando (cmd) execute:

robot --version
</ul>
  
<div align="left">
<img src="https://github.com/fabiosouthsystem/Instala-o-e-configura-o-Robot-Framework/blob/main/r5.png">

Maravilha!! seu Robot Framework está pronto para ser usado!!! Agora você pode escolher qual editor usar! eu utilizo por exemplo o Atom!
