# Dotfiles - Configuração Pessoal

Configurações do meu ambiente de desenvolvimento Linux com Hyprland + Waybar.

## Estrutura do Repositório

```
.dotfiles/
├── hypr/
│   └── hyprland.conf          # Configuração do Hyprland (window manager)
├── waybar/
│   ├── config                 # Configuração do Waybar (barra superior)
│   └── style.css             # Estilos CSS do Waybar
└── .config/
    └── gsimplecal/
        └── config            # Configuração do calendário
```

##  Tecnologias Utilizadas

- ** Hyprland** - Compositor/Window Manager Wayland
- ** Waybar** - Barra de status customizável
- ** gsimplecal** - Calendário popup
- ** Font Awesome** - Ícones na interface
- ** JetBrainsMono Nerd Font** - Fonte principal e ícones

##  Funcionalidades

### Waybar

-  **Volume** com controle por scroll
-  **Network** status WiFi/Ethernet
-  **CPU** usage com ícone personalizado
-  **RAM** usage e informações
-  **Relógio** com calendário clicável
-  **Bateria** com indicadores visuais
-  **Power** button para desligar

## Instalação

```bash
# Clone o repositório
git clone https://github.com/seuusuario/dotfiles.git ~/.dotfiles

# Instale dependências (Arch/Manjaro)
sudo pacman -S hyprland waybar gsimplecal ttf-font-awesome otf-font-awesome
```

---

**Status**: 🚧
