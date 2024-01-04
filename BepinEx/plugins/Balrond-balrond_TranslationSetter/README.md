
BalrondTranslationSetter is a name change/translation enforce tool. It let you create a translation/name change file for:
- monster(name)
- item(name & description)
- build piece ( name & description including container and table name)
- vegetation ( those who have Hover Text)

This is strictly Client side mod. it does not contain any syncs or other functionality required by server and should not be present on the server.

Whatever you put in text field will be enforced no matter your language setting or other translation files present in any mod. So if you put in swear word or whatever comes ot your mind that what you will see but ONLY you.
This also opens doors for at least partial translate for anything in language that was not yet supported by some mods(including mine) or even game itself.

Right now mod can not change nested text objects example : Smelter's input for ore and coal or any similar to objects

Translations are presented in json(example):
ONE PREFAB ID PER FILE.

File Name: ShipyardStation.json
{
    "prefabID":"ShipyardStation",
    "name":"UGA BUGA",
    "description":"SRATATA",
    "containerName":"",
    "tableName":"",
    "hoverName":""
}

Translations are stored in config folder "BalrondTranslationSetter/Translations" 
Folder will be generated upon first launch

A dump of all PrefabID that are able to be translated will be generated on first launch 
Dump will be stored in config folder under "BalrondTranslationSetter/Default" 

If after having a dump you will add more mods to the game and want to be able to edit them you need to remove the dump folder so it be generated again on new launch

Future plans:
- Add translations for Hugin Guide text
- Add translation for nested elements like input for Smelter


For support help and fun talks join 
Balrond's den Mods:
https://discord.gg/6zXPhAhpTk

