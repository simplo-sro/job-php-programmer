# SIMPLO - zadání pro PHP programátora

Vytvořte jednoduchou aplikaci, která bude sloužit jako API. Aplikace bude sloužit pro jednoduchou správu zákazníků. HTTP volání budou odvozena od architektury REST.

Aplikace se bude skládat z následujících entit:

### Customer

Konkrétní zákazník. Pro tuto entitu vytvořte end-point dle REST konvence. Atributy zvolte dle libosti.

### CustomerGroup

Zákaznická skupina. Zákazník může patřit do 0-N zákaznických skupin. Pro tuto entitu samostatný-end point vytvářet nemusíte. Stačí, když si data předem nachystáte například pomocí seedu.

## Požadavky na funkcionalitu

 - Vhodným způsobem zajistěte, aby šla vytvářet relace mezi zákazníkem a skupinou
 - Vhodným způsobem zajistěte, aby na vyžádání bylo možné současně s uživatelem získat data o uživatelských skupinách, do kterých patří
 - Použijte validační pravidla

Pro bonusové body použijte architekturu [PORTO](https://github.com/Mahmoudz/Porto)
