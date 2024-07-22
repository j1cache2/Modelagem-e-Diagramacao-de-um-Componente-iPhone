# [DIO](www.dio.me) - Trilha Java Básico

## Autores
- [João Luis](https://github.com/j1cache2)

### Modelagem e Diagramação de um Componente iPhone

### Diagrama UML (Mermaid)
```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()void
        +pausar()void
        +selecionarMusica(String musica)void
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
    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
```
