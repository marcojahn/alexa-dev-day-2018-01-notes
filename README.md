# Alexa Dev Day FFM Notes

## General
Zum Erzeugen einer neuen Lambda -> Standard Blueprint -> "facts"

**Ordnerstruktur** Vorschlag

	/lambda/custom
		/index.js // Lambda Code
	/models
		/de-DE.json // Skill
		/en-US.json
	skill.json
	LICENSE|README|...

## Links
- [Slides](alexa.design/slides)
- [skill testing](https://echosim.io)
- [Storywriter (zum Darstellen des Interaction Models)](https://storywriter.amazon.com/)
- [Skillinator](https://skillinator.io/)
- [Amazon 7 Facts for standout skills](https://alexa.design/standout)
- [Blog Sascha Wolter](http://www.wolter.biz/)

- [Alexa Links auf Deutsch](https://bit.ly/alexa-links)
- [Alexa Forum](https://alexa.design/forum)
- [Alexa contact us](https://alexa.design/contactus)
- [Alexa Tools](https://alexa.design/tools)
- [Alexa guide](https://alexa.design/guide)
- [Gleicher guide in deutsch](amzn.to/2DHAyJ9)
- [Alexa Labs Design](https://alexa.design/labs-design)
- [Alexa CLI](https://alexa.design/cli)
- [Echoshow](https://alexa.design/echoshow)
- [Notifications](alexa.design/notifications)
- [Labs-recipe](alexa.design/labs-recipe)
- [Labs-iot](alexa.design/labs-iot)
- [Resource Roundup: Top Alexa Tips and Tutorials for New Skill Builders](https://developer.amazon.com/de/blogs/alexa/post/82578e06-1733-49ee-a801-e5bea45b2686/resource-roundup-top-alexa-tips-and-tutorials-for-new-skill-builders)
- [Custom Interaction Model](https://developer.amazon.com/de/docs/custom-skills/custom-interaction-model-reference.html#custom-slot-syntax)

- [Skills SDK Node.JS](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs)

- [Speech Synthesis Markup Language](https://developer.amazon.com/de/docs/custom-skills/speech-synthesis-markup-language-ssml-reference.html)

- [Alexa Account binding / oAuth](https://developer.amazon.com/de/docs/custom-skills/link-an-alexa-user-with-a-user-in-your-system.html)
- [Alexa Skills mit lokalem node server entwickeln](http://www.wolter.biz/2017/02/amazon-alexa-im-lokalen-smart-home-programmieren/)

## Beispiele (Code)
- [Alexa Skills Cookbook](https://github.com/alexa/alexa-cookbook)
- [Alexa Skills Snippets](https://github.com/wolter/alexa-snippets)
- [Sample](https://alexa.design/labs-local)
- [High Low Game](https://github.com/wolter/skill-sample-nodejs-highlowgame)
- [State Game (outdated)](https://github.com/robm26/StateGame)
- [AVS Sample App](https://github.com/alexa/alexa-avs-sample-app)

## Sonstiges
- [magic mirror -> Alexa/aws](https://www.hackster.io/mexitek/magic-mirror-amazon-echo-and-aws-iot-29bba5)
- [Alexa / magic mirror](https://github.com/MichMich/MagicMirror/issues/1001)

### Skill/Lambda lokal testen/entwickeln
Eigener https endpoint
- [NGROK](https://ngrok.com/)
-> z.b. ngrok.io -> url setup -> im skill als eigener Endpunkt eintragen -> lokale Umgebung am laufen haben

Laufweg -> alexa -> internet -> AWS -> ngrok -> ssh tunnel -> lokaler rechner
