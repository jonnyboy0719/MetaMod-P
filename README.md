# MetaMod-P
Metamod is a plugin/DLL manager that sits between the Half-Life Engine and an HL Game mod, allowing the dynamic loading/unloading of mod-like DLL plugins to add functionality to the HL server or game mod. Metamod-P is enhanced version of Metamod. It has dynamic link-entities and automatic detection of Mod DLL and other improvement to allow it work with future Half-Life Engine updates and new Mods and updates. 

_____

Metamod Half-Life utility mod

See the files under "doc/txt" or "doc/html" for more information.

Will Day  
willday@metamod.org  
http://www.metamod.org/  

___

#What is special in this version of metamod?
- Hardcoded linkents have been replaced with dynamic linkents. No large list of entities that get outdated fast as new mods come and old ones update.
- Autodetects gamedll for unknown/new mods (so you don't have to use metamod-config to make Metamod-P work on those mods).
- Because of reasons above, you basicly never need to update metamod again anymore. This works all future mods and updates.
- Better performance/less CPU usage than original Metamod (by reducing executable size and therefore CPU cache pressure).

http://metamod-p.sourceforge.net/
