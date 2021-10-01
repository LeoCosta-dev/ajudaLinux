# Script de pós instalação para criar ambiente básico de desenvolvimento em Linux

## Fedora Linux 
![fedoralinuxlogo](https://cdn.icon-icons.com/icons2/1381/PNG/128/distributorlogofedora_94082.png)

## Execute as linhas uma de cada vez (São linhas únicas):
### **Para copiar ao terminal, utilize CTRL + C**
### **Para colar ao terminal, utilize CTRL + SHIFT + V**

<br>

```sudo dnf update && sudo dnf upgrade -y && sudo dnf install git -y && sudo dnf install nodejs -y && sudo dnf install vlc -y && sudo dnf install npm -y && sudo dnf install yarn -y && sudo dnf install pip -y && sudo dnf install snapd -y && snap install spotify && snap install insomnia && wget "https://go.microsoft.com/fwlink/?LinkID=620884" -O vscode.tar.gz && sudo tar -vzxf vscode.tar.gz -C /opt/ && sudo mv /opt/VSCode*/ /opt/vscode/ && sudo ln -sf /opt/vscode/code /usr/bin/code && echo -e '[Desktop Entry]\n Version=1.0\n Name=vscode\n Exec=/opt/vscode/code\n Icon=/opt/vscode/resources/app/resources/linux/code.png\n Type=Application\n Categories=Application' | sudo tee /usr/share/applications/vscode.desktop && wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.rpm && sudo dnf install ./google-chrome-stable_current_amd64.rpm -y && sudo snap install discord && wget https://zoom.us/client/latest/zoom_amd64.deb -O zoom.rpm && sudo apt install ./zoom.rpm -y && reboot```

## Feito!