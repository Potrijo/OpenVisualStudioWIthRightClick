https://onlinestringtools.com/escape-string // Change to double slash

ATTENTION: rf.reg file is an example

Create a file.reg
fill up with the following content:

Windows Registry Editor Version 5.00
 
	[HKEY_CLASSES_ROOT\*\shell\VSCode]
	@="Abrir con Visual Studio Code"
	"Icon"=" PEGAR_AQUI "
 
	[HKEY_CLASSES_ROOT\*\shell\VSCode\command]
	@="\" PEGAR_AQUI \" \"%1\""
 
	Windows Registry Editor Version 5.00
 
	[HKEY_CLASSES_ROOT\Directory\shell\VSCode]
	@="Abrir con Visual Studio Code"
	"Icon"=" PEGAR_AQUI "
 
	[HKEY_CLASSES_ROOT\Directory\shell\VSCode\command]
	@="\" PEGAR_AQUI \" \"%V\""
 
	Windows Registry Editor Version 5.00
 
	[HKEY_CLASSES_ROOT\Directory\Background\shell\VSCode]
	@="Abrir con Visual Studio Code"
	"Icon"=" PEGAR_AQUI "
 
	[HKEY_CLASSES_ROOT\Directory\Background\shell\VSCode\command]
	@="\" PEGAR_AQUI \" \"%V\"" 
  
  Replace the content "PEGAR_AQUI" by your visual Code shortCut path
