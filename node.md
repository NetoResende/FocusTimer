## Fhosphoricons.com  -- < biblioteca de icons para o html. >
    {
        (ÍCONS DA BIBLIOTEACA -phosphoricons.com ):
        ph ph-play-circle  - play
        ph ph-pause-circle - pausa
        ph ph-timer        - tempo
        ph ph-stop-circle - para
        ph ph-speaker-none - som
        ph ph-speaker-high - /som
    }



## regra de teste para aceitar somente números ..

       ex: [
            el.minutes.onkeypress = (event) => /\d/.test(event.key)
        ]


## construtor de audio /.wav/.mp3
        ex:[
           export const buttonPress = new Audio('./assets/audio.mp3') 
        ]

        ex:[

            execultando o audio >>>>>>     buttonPress.paly()
        ]