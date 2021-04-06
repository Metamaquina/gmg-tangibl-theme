# Tangibl

Tema customizado para MediaGoblin.

## Instalação

Vá até a pasta onde sua instância do MediaGoblin está localizada, navegue até a 
pasta themes e rode:

    $ git clone git@github.com:Metamaquina/mediagoblin-tangibl-theme.git

Altere no `mediagoblin_local.ini`, dentro da seção `[mediagoblin]` a seguinte linha:
    
    theme = gmg-tangibl-theme

E, para servir os arquivos estáticos, rode:

    $ ./bin/gmg assetlink

Pronto, agora sua instância do MediaGoblin rodará com o tema Tangibl.
