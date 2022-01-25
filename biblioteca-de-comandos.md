## Bash Command Line
- Linux
- MacOs
- Bash
- Zsh

### Versão da distribuição

uname --help
uname -v
    
#### Modo Root

__Habilitar Root:__

sudo passwd root

__Desabilitar:__

su root 
sudo passwd -l(pype)root

__Entrar Root:__
su root
senha

__Sair modo Root:__

exit

#### Obs instalação programas

.deb abre direto no instalador padrão gnome do ZorinOS(Ubutntu)

### Compilar/executar algoritmos C++

g++ nome_programa.cc -o nome_para_execucao

./nome_para_execucao

Obs: 
1. Utilizando o compilador GCC já instalado na máquina
2. Para compilar algoritmos em C basta alterar o nome do compilador para "gcc"
 
### Compilando java

javac Codigo.java    // nome da classe igual ao nome do arquivo

java Codigo.class  // se der erro, tentar sem o .class

Obs:
1. Com JDK e JVM já instalados.

### Renomar diretorio

mv nomeDoDiretorio novoNomeDoDiretorio

### Listar diretorios
* ls 
* dir 


### Diretorios

* [pw]: verificar qual diretorio atual 
* [cd -]: para retornar ao diretorio anterior
* [..] : diretorio superior

* /home/nome_usuario - diretorio do usuario para arquivos pessoais do usuario
 
Apagar diretoria vazio
* $ rm -r nome_file 

### Ejetar pendrive

umount /media/$username/$diskname

### Procurar 
* which x 

### Listar de utilitarios e informacoes dos discos
* Diskuti list
