# Script de pós instalação para criar ambiente básico de desenvolvimento em Linux

## Ubuntu, Debian, e Derivados
![ubuntu](https://cdn.icon-icons.com/icons2/70/PNG/128/ubuntu_14143.png)

## Execute as linhas uma de cada vez (São linhas únicas):
### **Para copiar ao terminal, utilize CTRL + C**
### **Para colar ao terminal, utilize CTRL + SHIFT + V**

<br>

```sudo apt update && sudo apt upgrade -y && sudo apt install git -y && sudo apt install nodejs -y && sudo apt install vlc -y && sudo apt install npm -y && sudo apt install yarn -y && sudo apt install pip -y && sudo apt install snapd -y && snap install spotify && snap install insomnia && wget "https://go.microsoft.com/fwlink/?LinkID=620884" -O vscode.tar.gz && sudo tar -vzxf vscode.tar.gz -C /opt/ && sudo mv /opt/VSCode*/ /opt/vscode/ && sudo ln -sf /opt/vscode/code /usr/bin/code && echo -e '[Desktop Entry]\n Version=1.0\n Name=vscode\n Exec=/opt/vscode/code\n Icon=/opt/vscode/resources/app/resources/linux/code.png\n Type=Application\n Categories=Application' | sudo tee /usr/share/applications/vscode.desktop && wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb && sudo apt install ./google-chrome-stable_current_amd64.deb -y && sudo snap install discord && wget https://zoom.us/client/latest/zoom_amd64.deb -O zoom.deb && sudo apt install ./zoom.deb -y && reboot```

<br>

## Feito!