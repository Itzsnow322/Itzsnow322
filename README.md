class mj:
    def __init__(self):
        self.role         = ["Frontend Developer", "Backend Developer"]
        self.student      = "Software Engineering"
        self.location     = "Colombia"

        self.os           = ["GNU/Linux", "Windows"]
        self.distros      = ["CachyOS", "NixOS"]

        self.languages    = [
            "Python",
            "Java",
            "JavaScript",
            "TypeScript",
            "C",
            "C++"
        ]

        self.technologies = {
            "frontend": [
                "React",
                "HTML",
                "CSS",
                "Tailwind"
            ],

            "backend": [
                "Node.js",
                "FastAPI",
                "Flask"
            ],

            "databases": [
                "PostgreSQL",
                "MySQL"
            ],

            "linux": [
                "Hyprland",
                "Fish",
                "Neovim",
                "Bash"
            ],

            "tools": [
                "Git",
                "GitHub",
                "Docker",
                "VSCode"
            ]
        }

        self.current_focus = [
            "Full Stack Development",
            "GNU/Linux",
            "Hyprland Ricing",
            "Low Level Stuff"
        ]

    def __str__(self):
        return "fixing one bug and creating three more."

me = mj()

print(me)

# booting /life...
# loading configs...
# starting chaos...
