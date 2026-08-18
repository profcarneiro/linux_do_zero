# Instalação do VNC no Linux Mint

1. **Instalação do x11vnc**:
```bash 
sudo apt update; sudo apt install x11vnc
```
2. **Configurando uma senha para o VNC:**
```bash
x11vnc -storepasswd
```
3. **Iniciando o servidor VNC:**
```bash
x11vnc -usepw -display :0 -forever -bg 
```
(adicionar aos aplicativos de incialização)