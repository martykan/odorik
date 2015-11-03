# Odorik
Je to tzv. single page application a využívá jen JavaScript, HTML a CSS a API . Pokud si ji tedy stáhnete (např. dáte "uložit jako ..." ), můžete je pouštět i lokálně nebo z jiných webových stránek, na které jej umístíte.
Pro přihlášení se zadává API přihlašovací jméno a API heslo, které najdete po přihlášení v Nastavení účtu -> Api heslo.
Hlavní výhoda je v tom, že osobě, která danou aplikaci používá, nemusíte prozrazovat běžné přihlašovací údaje. API jméno a heslo je uloženo pomocí cookies lokálně na prohlížeči a můžete je tak uložit při prvním použití osobně.

V hlavičce najdete nastavení, ve kterém si můžete veškeré funkce přispůsobit.

Podle zájmu můžeme přidat možnost nastavovat další volby obdobným způsobem. Tento web lze snadno integrovat se zbytkem firemního webu a jeho uživatel nebude zmaten spoustou jiných voleb, které Odorik.cz sice umožňuje, ale koncový uživatel linky je nikdy nevyužije. Podobným způsobem můžeme dovolit i přístup k historii hovorů, pokud by byl zájem.

Dokumentaci API najdete na: http://www.odorik.cz/w/api

## Nastavení v hlavičce
API uživatelské jméno a heslo - automatické přihlášení

    var APIuser = "1234560";
    var APIpass = "abc9de99";

Zamknutá čísla - čárkou oddělený seznam zkratek (klapek), které nejde editovat

    var lockedNumbers = "1,7"; // zakáže čísla 1 a 7

Skrytí zamknutých čísel - nezobrazovat vůbec, nebo zobrazit, ale zakázat úpravy

    var hideLockedNumbers = true; // nezobrazí je vůbec 
    
Povolit přidávání nových čísel

    var enableAdding = false; // zakáže přidávání

Povolit upravování nových čísel

    var enableEditing = true; // povolí úpravy

Povolit mazání čísel

    var enableRemoving = false; // zakáže mazání

Povolit callback

    var enableCallback = false; // zakáže callback

Povolit políčko rychlého callbacku

    var enableQuickCallback = false; // zakáže políčko rychlého callbacku

Povolit odhlašovaní uživatele

    var enableLogout = false; // zakáže odhlašování

Povolit import/export

    var enableLogout = false; // zakáže import/export

Povolit úpravu přímo v tabulce - dvojklikem na číslo jej můžete přímo upravit

    var enableInlineEditing = false; // zakáže úpravy přímo v tabulce

Povolit animace

    var enableAnimations = false; // zakáže animace

Přednastavené číslo pro callback

    var defaultCallbackNumber = "0085023815827"; // nastaví výchozí číslo pro callback na 0085023815827

Povolit tmavé téma - vhodné pro osoby se zrakovými problémy

    var darkTheme = true; // povolí tmavé téma
