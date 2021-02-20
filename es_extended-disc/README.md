# es_extended 
disc versiyonu %100 çalışır durumda

## Gereksinimler

Gerekli Programlar.

- [mysql-async](https://github.com/brouznouf/fivem-mysql-async)
- [essentialmode](https://github.com/kanersps/essentialmode)
- [esplugin_mysql](https://github.com/kanersps/esplugin_mysql)
- [async](https://github.com/ESX-Org/async)

## İndirme ve Kurulum

### indirmeler

```
fvm install --save --folder=essential esx-org/es_extended
fvm install --save --folder=esx esx-org/esx_menu_default
fvm install --save --folder=esx esx-org/esx_menu_dialog
fvm install --save --folder=esx esx-org/esx_menu_list
```

### Github kullanma

```
cd resources
git clone https://github.com/ESX-Org/es_extended [essential]/es_extended
git clone https://github.com/ESX-Org/esx_menu_default [esx]/[ui]/esx_menu_default
git clone https://github.com/ESX-Org/esx_menu_dialog [esx]/[ui]/esx_menu_dialog
git clone https://github.com/ESX-Org/esx_menu_list [esx]/[ui]/esx_menu_list
```

### Manuel olarak kurulum

- İndir https://github.com/ESX-Org/es_extended/releases/latest
- İçine koy `resource/[essential]` dizin
- İndir https://github.com/ESX-Org/esx_menu_default/releases/latest
- İçine koy `resource/[esx]/[ui]` dizin
- İndir https://github.com/ESX-Org/esx_menu_dialog/releases/latest
- İçine koy `resource/[esx]/[ui]` dizin
- İndir https://github.com/ESX-Org/esx_menu_list/releases/latest
- İçine koy `resource/[esx]/[ui]` dizin

### Kurulum

- yazdor `es_extended.sql` bunu databae ye.
- cfg ye yaz start ver `server.cfg` .

```
start mysql-async
start essentialmode
start esplugin_mysql

start es_extended

start esx_menu_default
start esx_menu_list
start esx_menu_dialog
```
