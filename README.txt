=== Reco Widget by AngryCreative.se ===
Contributors: plux, angrycreative
Tags: reco, widget, recommendation, recos
Requires at least: 3.0
Tested up to: 3.3.1
Stable tag: 0.2

Shows a widget from the Swedish customer Community Reco.se.

== Description ==

**Notice: This plugin are only in Swedish as the site that powers the plugin only are avible in Swedish at the moment**

Vi på webbyrån [Angry Creative](http://www.angrycreative.se) bestämde oss för att göra det extremt enkelt att visa upp på din företags hemsida vad dina kunder tycker om dig i realtid, därför utvecklade vi den här Wordpress pluggen.

All utveckling av pluggen kommer att ske på våran [Github sida](https://github.com/Angrycreative/reco-widget) där du också kan rapportera [buggar.](https://github.com/Angrycreative/reco-widget/issues)
 
Du kan också läsa mer om pluggen på [våran egen sida](http://www.angrycreative.se/oppen-kallkod/reco-for-wordpress/) och på [reco-bloggen](http://blogg.reco.se/)

== Installation ==

För att kunna använda den här pluginen så måste du ha en API-nyckel från reco.
Om du är kund hos reco så är det väldigt enkelt att få fram uppgifterna du behöver. (Annars kan du skicka ett mail till api[at]reco.se för att ansöka som en API-nyckel och det speciella företags-ID som behövs för att kunna använda pluggen)

Gör så här för att enkelt visa dina recos på din Wordpress sajt:

1. Ladda upp hela katalogen från zip-filen till `/wp-content/plugins/`katalogen på din webserver.
1. Aktivera pluggen genom admin-sidan på din site som vanligt.
1. Skapa en sida eller ett inlägg och lägg shortcoden `[reco-widget]` där du vill l visa dina recos.

Om du är företags kund hos reco så gör du så här för att hitta din API-nyckel och ditt företags-ID:

1. Logga in på reco.se och gå till ditt företags profilsida.
1. Klicka på knappen API på sidan (visas för alla företagsadministratörer).
1. Nu visas en popup med två viktiga värden. Dels din API-nyckel och dels ditt företags API-ADI. Båda behövs för att kunna använda vårt API. Då får också en exempel länk till en json-fil som uppdateras dynamiskt med ny information allteftersom företaget får nya recos.
![api popup](http://blogg.reco.se/wp-content/uploads/2012/02/API-nyckel-och-ftg-ID-480x359.png "API Popup på reco.se")
1. Logga in på admin-sidan på din Wordpress sida och gå till Inställningar -> Reco Widget
1. Fyll i API-nyckel och företags-ID och ange hur många recos du vill visa på sajten.
1. Klicka på Spara Ändringar

== Changelog ==

= 0.2 =
Fixing a small issue with incorrect links.

= 0.1 =
* Initial version.




