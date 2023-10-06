# eznord
Simple bash front-end for nordvpn.

Copy contents of the ```eznord``` file to your ```.bash_aliases``` file.

Use ```nc <Country name, country code, city>``` to connect or ```nc``` to connect to default location.
You can change default location by changing country code in ```ncon``` function.

For example:
```
country="${1:-ch}"
```
sets the default location to Switzerland,
```
country="${1:-us}"
```
sets the default location to USA.

Use ```nd``` to disconnect.

Use ```ns``` to see the status of your connection.
