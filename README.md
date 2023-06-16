<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.art

വെബ്‌സൈറ്റ് കോഡിന്റെ ഒരു ഭാഗം ഓപ്പൺ സോഴ്‌സാണ്, വിവർത്തനം ഒപ്റ്റിമൈസ് ചെയ്യാൻ സഹായിക്കുന്നതിന് സ്വാഗതം.

## ഫ്രണ്ട്-എൻഡ് കോഡ്

* [ഫ്രണ്ട്-എൻഡ് കോഡ്](https://github.com/xxai-art/web)
* [സൈറ്റിന്റെ മൊത്തത്തിലുള്ള ഭാഷാ പായ്ക്കുകൾ](https://github.com/xxai-art/web/tree/main/i18n)
* [ലോഗിൻ മൊഡ്യൂളുകൾക്കുള്ള ഭാഷാ പായ്ക്കുകൾ](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [വെബ്സൈറ്റ് ബഹുഭാഷാ ഡോക്യുമെന്റേഷൻ](https://github.com/xxai-doc)

ഫ്രണ്ട്-എൻഡ് പ്രോഗ്രാമിംഗ് ഭാഷ [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) ആണ്, അത് കോഫിസ്ക്രിപ്റ്റ് വാക്യഘടനയെ അടിസ്ഥാനമാക്കി ചില സവിശേഷതകൾ ചേർക്കുന്നു, കാണുക [./coffee_plus.md](./coffee_plus.md) .

## വെബ്സൈറ്റുകളുടെയും ഡോക്യുമെന്റുകളുടെയും അന്താരാഷ്ട്രവൽക്കരണം

ഇനിപ്പറയുന്ന 3 പ്രോജക്റ്റുകളിൽ നിർമ്മിക്കുക

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  പ്രത്യയം `.mdt` ആണ്, നിങ്ങൾക്ക് ബാഹ്യ ഫയലുകൾ റഫർ ചെയ്യുന്നതിന് `<+ ./coffee_plus/import.js>` എന്നതിന് സമാനമായ വാക്യഘടന ഉപയോഗിക്കാം, കൂടാതെ `.md` എന്ന പ്രത്യയം ഉപയോഗിച്ച് മാർക്ക്ഡൗൺ സൃഷ്ടിക്കുകയും ചെയ്യാം.

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  മാർക്ക്ഡൗൺ വിവർത്തനം കോഡുകളും ലിങ്കുകളും വിവർത്തനം ചെയ്യില്ല, വിവർത്തനം ചെയ്ത വാക്യങ്ങൾ കാഷെ ചെയ്യും. വിവർത്തനം പരിഷ്കരിച്ചെങ്കിലും യഥാർത്ഥ വാചകം പരിഷ്കരിച്ചിട്ടില്ലെങ്കിൽ, അത് വീണ്ടും എക്സിക്യൂട്ട് ചെയ്യുന്നത് വിവർത്തനത്തിന്റെ പരിഷ്ക്കരണത്തെ തിരുത്തിയെഴുതില്ല.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  `yaml` സൃഷ്‌ടിച്ച വെബ്‌സൈറ്റുകൾ വിവർത്തനം ചെയ്യുന്നതിനുള്ള ഭാഷാ ഫയലുകൾ.
