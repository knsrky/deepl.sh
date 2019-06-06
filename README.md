# deepl.sh
DeepL shell translator. It works!

### References
Based on method used in Alfred Deepl Plugin. Its code has more bloat, uses own libs instead repo one and don't work correctly from time to time. Method is pretty simple, it's just curling of deepl json shit.

### Dependencies:
`jq`

### Using:
1. (Optional) Open deepl.sh and change "DE" at lines 4 and 39 to target language.
* `deepl.sh "Your text"`
2. Instead of it you can
* `deepl.sh -l LANG "Your text"`

##### Languages:
`EN, DE, FR, RU, SP, PT, IT, DU, PO`
