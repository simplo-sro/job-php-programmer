# SIMPLO - zadání pro PHP programátora

Vytvořte v [Laravelu](https://laravel.com/) jednoduchou aplikaci, která bude sloužit jako API. Aplikace bude sloužit pro 
jednoduchou správu zákazníků. Navržená API by měla splňovat všechny principy RESTu a používat JSON pro výměnu dat.

K tvorbě aplikace nepoužívejte žádné balíčky.

Aplikace se bude skládat z následujících entit:

### Customer

Konkrétní zákazník. Pro tuto entitu vytvořte end-point dle REST konvence. Atributy zvolte dle libosti.

### CustomerGroup

Zákaznická skupina. Zákazník může patřit do 0-N zákaznických skupin. Pro tuto entitu samostatný resource vytvářet nemusíte. 
Stačí, když si data předem nachystáte, například pomocí seedu.

## Požadavky na funkcionalitu

 - Vhodným způsobem zajistěte, aby šla vytvářet relace mezi zákazníkem a skupinou (POST/PUT na resource zákazníka)
 - Vhodným způsobem zajistěte, aby na vyžádání bylo možné současně s uživatelem získat data o uživatelských skupinách (GET na resource zákazníka)
 - Vstupy aplikace musí být validovány

Pro bonusové body použijte architekturu [PORTO](https://github.com/Mahmoudz/Porto), volitelně i Repository Pattern

**Úkol prosím odevzdejte tak, že nahrajete zdrojový kód na Git a pošlete odkaz na repozitář.**
