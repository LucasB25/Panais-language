# 🌍 Multilanguage Support for Panais 🎶

## 🌟 How to Add a New Language

1. 📁 Create a new file in the `locales` directory with the name of the language in the format `language_code.json`. For example, `EnglishUS.json` for English, `SpanishES.json` for Spanish, etc.
2. 📋 Copy the contents of the `EnglishUS.json` file into the new file.
3. 🌐 Translate the strings in the new file to the desired language.

### 📚 Available Translations

- [x] English (US) - `EnglishUS.json` (Default)
- [x] French - `French.json` [by @LucasB25](https://github.com/LucasB25)

- [ ] Hindi - `Hindi.json` (Not Started)
- [ ] Spanish (ES) - `SpanishES.json` (Not Started)
- [ ] Portuguese (PT) - `PortuguesePT.json` (Not Started)
- [ ] Polish - `Polish.json` (Not Started)
- [ ] German - `German.json` (Not Started)
- [ ] Russian - `Russian.json` (Not Started)
- [ ] Korean - `Korean.json` (Not Started)
- [ ] Indonesian - `Indonesian.json` (Not Started)
- [ ] English (GB) - `EnglishGB.json` (Not Started)
- [ ] Bulgarian - `Bulgarian.json` (Not Started)
- [ ] Chinese (CN) - `ChineseCN.json` (Not Started)
- [ ] Chinese (TW) - `ChineseTW.json` (Not Started)
- [ ] Croatian - `Croatian.json` (Not Started)
- [ ] Czech - `Czech.json` (Not Started)
- [ ] Danish - `Danish.json` (Not Started)
- [ ] Dutch - `Dutch.json` (Not Started)
- [ ] Finnish - `Finnish.json` (Not Started)
- [ ] Greek - `Greek.json` (Not Started)
- [ ] Hungarian - `Hungarian.json` (Not Started)
- [ ] Italian - `Italian.json` (Not Started)
- [ ] Japanese - `Japanese.json` (Not Started)
- [ ] Lithuanian - `Lithuanian.json` (Not Started)
- [ ] Norwegian - `Norwegian.json` (Not Started)
- [ ] Portuguese (BR) - `PortugueseBR.json` (Not Started)
- [ ] Romanian - `Romanian.json` (Not Started)
- [ ] Swedish - `Swedish.json` (Not Started)
- [ ] Thai - `Thai.json` (Not Started)
- [ ] Turkish - `Turkish.json` (Not Started)
- [ ] Ukrainian - `Ukrainian.json` (Not Started)
- [ ] Vietnamese - `Vietnamese.json` (Not Started)

## 📚 How to Use the Translations

2. 📋 Copy the contents of the `EnglishUS.json` file into the new file.

3. 🌐 Translate the strings in the new file to the desired language.

## Have a language to contribute? 🎉
- Fork the repository.
- Add the translation file in the `locales` directory.
- Create a pull request with the changes.

## 📝 Translation Guidelines

- **Do not** change the key names in the translation JSON file.
- **Do not** change the structure of the translation JSON file.
- **Do not** remove the `{}` tags from the strings.
- **Do not** add any new keys to the translation JSON file.
- **Do not** add any new directories to the repository.

### Example Translation JSON

**EnglishUS:**
```json
{
	"cmd": {
		"ping": {
			"description": "Displays the bot's ping.",
			"content": "`🏓` | Pinging...",
			"bot_latency": "Bot Latency:",
			"api_latency": "API Latency:",
			"requested_by": "Requested by: {author}"
		}
	}
}
```

**French:**
```json
{
	"cmd": {
		"ping": {
			"description": "Affiche le ping du bot.",
			"content": "`🏓` | En train de pinger...",
			"bot_latency": "Latence du Bot :",
			"api_latency": "Latence de l'API :",
			"requested_by": "Demandé par : {author}"
		},
	}
}
```

### Formatting Tags for i18n NPM
To ensure `{}` are not removed during translations, use the format tags: `["{", "}"]`.


## 📚 Resources
- [i18n NPM](https://www.npmjs.com/package/i18n)
- [Discord Developer Portal - Locales](https://discord.com/developers/docs/reference#locales)
