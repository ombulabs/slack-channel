# Slack Channel

A script to see the last messages in a particular channel.

## Installation

Before you can call this you must add your Slack token to the `.env` file

In order to get your Slack token, you can go here: [https://api.slack.com/docs/oauth-test-tokens](https://api.slack.com/docs/oauth-test-tokens)

## Usage

    ./bin/slack-channel #gifs

    2016-11-10 09:26 - @etagwerker: "@mauro-oto vos tenías un código en ruby que leía mensajes de <#C02BW1AB7|general> para la app de :pingpong: no?"
    2016-11-10 09:27 - @mauro-oto: "@etagwerker si"
    2016-11-10 09:27 - @etagwerker: "es código abierto ó lo tenés en un repo privado?"
    2016-11-10 09:28 - @mauro-oto: "<https://github.com/ombulabs/ombu-ping-pong-tracker/blob/master/lib/tasks/slack_matches.rake>"
    2016-11-10 09:44 - @etagwerker: "@mauro-oto de dónde sale el token?"
    2016-11-10 09:46 - @mauro-oto: "<https://github.com/ombulabs/ombu-ping-pong-tracker/blob/master/app/services/slack_service.rb>, se la paso via las variables de entorno de Heroku, o decis de donde lo sacas en la app de Slack?"
    2016-11-10 09:47 - @etagwerker: "@mauro-oto claro, de Slack, estoy haciendo un script para probar algo"
    2016-11-10 09:48 - @mauro-oto: "ah, hmm, no me acuerdo de donde lo encontraba, parece que cambio un poco, fijate si te sirve esta: <https://api.slack.com/docs/oauth-test-tokens>"
    2016-11-10 10:15 - @etagwerker: "ah, copado, está bueno que tienen el concepto de \"test tokens\""
    Done!
    etagwerker:slack-channel/ (master✗) $ ./bin/slack-channel ombulabs

## Contributions

We are open to contributions! 
