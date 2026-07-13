class MJ:
    def __init__(self):
        self.role      = ["Frontend", "Backend", "Fullstack"]
        self.os        = "NixOS"
        self.wm        = "niri"          # ex-Hyprland, RIP mi rice morado
        self.shell     = "fish"
        self.editor    = ["Neovim", "VSCode"]
        self.aesthetic = "monocromo + neon sutil"
        self.currently = "riceando el desktop otra vez"

    def __str__(self):
        return "arreglando un bug, creando tres más — pero con estilo"

mj = MJ()
print(mj)
