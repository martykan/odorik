# Odorik
Je to tzv. single page application a využívá jen JavaScript, HTML a CSS a API . Pokud si ji tedy stáhnete (např. dáte "uložit jako ..." ), můžete je pouštět i lokálně nebo z jiných webových stránek, na které jej umístíte.
Pro přihlášení se zadává API přihlašovací jméno a API heslo, které najdete po přihlášení v Nastavení účtu -> Api heslo.
Hlavní výhoda je v tom, že osobě, která danou aplikaci používá, nemusíte prozrazovat běžné přihlašovací údaje. API jméno a heslo je uloženo pomocí cookies lokálně na prohlížeči a můžete je tak uložit při prvním použití osobně.

V hlavičce najdete nastavení, ve kterém si můžete veškeré funkce přispůsobit.

Podle zájmu můžeme přidat možnost nastavovat další volby obdobným způsobem. Tento web lze snadno integrovat se zbytkem firemního webu a jeho uživatel nebude zmaten spoustou jiných voleb, které Odorik.cz sice umožňuje, ale koncový uživatel linky je nikdy nevyužije. Podobným způsobem můžeme dovolit i přístup k historii hovorů, pokud by byl zájem.

Dokumentaci API najdete na: http://www.odorik.cz/w/api

## Nastavení v hlavičce
API uživatelské jméno a heslo - automatické přihlášení

    var APIuser = "";
    var APIpass = "";

Zamknutá čísla - čárkou oddělený seznam zkratek (klapek), které nejde editovat

    // př. var lockedNumbers = "1,7" // zakáže čísla 1 a 7
    var lockedNumbers = "";

Skrytí zamknutých čísel - nezobrazovat vůbec, nebo zobrazit, ale zakázat úpravy

    // př. var hideLockedNumbers = true // nezobrazí vůbec 
    var hideLockedNumbers = true;

Povolit přidávání nových čísel

    // př. var enableAdding = false // zakáže přidávání
    var enableAdding = true;

Povolit upravování nových čísel

    // př. var enableEditing = true // povolí úpravy
    var enableEditing = true;

Povolit mazání nových čísel

    // př. var enableRemoving = false // zakáže mazání
    var enableRemoving = true;

Povolit callback

    // př. var enableCallback = false // zakáže callback
    var enableCallback = true;

Povolit políčko rychlého callbacku

    // př. var enableQuickCallback = false // zakáže políčko callbacku
    var enableQuickCallback = true;

Povolit odhlašovaní uživatele

    // př. var enableLogout = false // zakáže odhlašování
    var enableLogout = true;

Povolit import/export

    // př. var enableLogout = false // zakáže import/export
    var enableImportExport = true;

Povolit úpravu přímo v tabulce - dvojklikem na číslo jej můžete přímo upravit

    // př. var enableInlineEditing = false // zakáže úpravy přímo v tabulce
    var enableInlineEditing = true;

Povolit animace
    
    // př. var enableAnimations = false // zakáže animace
    var enableAnimations = true;

Přednastavené číslo pro callback

    // př. var defaultCallbackNumber = "0085023815827"; // nastaví výchozí číslo pro callback na 0085023815827
    var defaultCallbackNumber = "";

Povolit tmavé téma - vhodné pro osoby se zrakovými problémy

    // př. var darkTheme = true // povolí tmavé téma
    var darkTheme = false;> 
