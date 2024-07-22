# Modelagem-e-Diagramacao-de-um-Componente-iPhone
Modelagem e Diagramação de um Componente iPhone - Projeto da DIO

classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }
[![](https://mermaid.ink/img/pako:eNptks1uwjAMx1-lyqnT4AV6mIS2yw5DCKYdpl5MYlpLqV25CdpAvPsClI-u5JL4H8c_2_HeWHFoCmM9dN0bQaXQlJyldVKyJbYqLgbRj9iRBZ_tz9fH9RzEguZPd0oLsfsndejRkjD0IfJVUOIqa05W73ko-R47a0HR1_KZ3m6EycqA66lKkD4OxwZV7okQkB0Os6AUhEBfRRVJvmSXPybPYYsVONF3DqiMYQDGH1qTLqAivtYR1Q_gjs7VzmULszXkw8wieNrBJcTjHGhRC-MFfL3s5en0ZfwtI49xB0cuo1LNxKRWNkAuTcSJXppQY4OlKW7Hkg_JERJ89cvWFEEjToxKrGpTbMB3yYqtS5_Qz9NVbYG_RW42OjpW0E_gcTv8AWkX06A?type=png)](https://mermaid.live/edit#pako:eNptks1uwjAMx1-lyqnT4AV6mIS2yw5DCKYdpl5MYlpLqV25CdpAvPsClI-u5JL4H8c_2_HeWHFoCmM9dN0bQaXQlJyldVKyJbYqLgbRj9iRBZ_tz9fH9RzEguZPd0oLsfsndejRkjD0IfJVUOIqa05W73ko-R47a0HR1_KZ3m6EycqA66lKkD4OxwZV7okQkB0Os6AUhEBfRRVJvmSXPybPYYsVONF3DqiMYQDGH1qTLqAivtYR1Q_gjs7VzmULszXkw8wieNrBJcTjHGhRC-MFfL3s5en0ZfwtI49xB0cuo1LNxKRWNkAuTcSJXppQY4OlKW7Hkg_JERJ89cvWFEEjToxKrGpTbMB3yYqtS5_Qz9NVbYG_RW42OjpW0E_gcTv8AWkX06A)
    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
