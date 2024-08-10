# Jak nainstalovat pterodactyl s SSL certifikátem krom po kroku


**V prvním kroku se přihlásíme do SSH klienta.**

Poté se příhlásíme jako root.


**V druhém kroku naistalujeme curl pokud jej nemáme.**

Pokud nemáte naistalovaný curl, nainstalujeme jej abychom mohli pokračovat.


**V třetím kroku začneme s instalací samotného panelu.**

Jestliže máte curl nainstalovaný, začneme s instalací samotného Pterodactyl panelu. Využíjeme instalační příkaz, který nám to zjednodušší.
```bash
bash <(curl -s https://pterodactyl-installer.se)
```

:warning: Pokud nebude využívat z níže uvedených operačních systému, nebude vám to fungovat.

### Podporované operační systémy

| Operační systém  | Verze   | Podpora            | PHP Verze   |
| ---------------- | ------- | ------------------ | ----------- |
| Ubuntu           | 14.04   | :red_circle:       |             |
|                  | 16.04   | :red_circle: \*    |             |
|                  | 18.04   | :red_circle: \*    | 8.1         |
|                  | 20.04   | :white_check_mark: | 8.1         |
|                  | 22.04   | :white_check_mark: | 8.1         |
|                  | 24.04   | :white_check_mark: | 8.1         |
| Debian           | 8       | :red_circle: \*    |             |
|                  | 9       | :red_circle: \*    |             |
|                  | 10      | :white_check_mark: | 8.1         |
|                  | 11      | :white_check_mark: | 8.1         |
|                  | 12      | :white_check_mark: | 8.1         |
| CentOS           | 6       | :red_circle:       |             |
|                  | 7       | :red_circle: \*    |             |
|                  | 8       | :red_circle: \*    |             |
| Rocky Linux      | 8       | :white_check_mark: | 8.1         |
|                  | 9       | :white_check_mark: | 8.1         |
| AlmaLinux        | 8       | :white_check_mark: | 8.1         |
|                  | 9       | :white_check_mark: | 8.1         |


**Ve čtvrtém kroku začneme s odpovídám na dotazy, které nám to bude klást.**
*Pokračování příště, během pár dnů/týdnů to přibyde*
