## Fråga 1: Versionshantering vs vanliga filer
Versionshantering innebär att man sparar ett projekts historik och inte bara den senaste versionen. 
Skillnaden mellan att spara en fil i editorn och att spara i Git är att i editorn sparas endast den senaste versionen och om då datorn skulle krascha så är allt borta. Om du istället sparar i Git så sparas varje commit som ett fryst ögonblick i historiken och ligger säkert på GitHub.
GitHubs historik är som ett bevis på arbetets utveckling så man kan följa varje commit och se hur arbetets flöde har gått till.
## Fråga 2: Arbetsytan, Staging och Commits
Git status visar vilka filer som har ändrats och vad som ligger i staging. Git add lägger de valda ändringarna i staging så att de kan sparas. Git commit skapar som ett fryst ögonblick av projektet. Arbetsytan är som arket där du jobbar, staging är som kuvertet där du lägger det som ska sparas och commit är som arkivlådan där git arkiverar ögonblicksbilden.
Git protesterar med "no changes added to commit" när kuvertet är tomt, att du alltså inte har kört git add på de ändrade filerna.
## Fråga 3: Lådan hemma vs Montern på GitHub
Man kan säga att mappen på din dator är den lokala arbetsytan och att repot på GitHub är den publicerade kopian. Git push skickar dina commits från "lådan hemma" (datorn) till "glasmontern" på GitHub så historiken uppdateras där.
Att git push svarar "everything up-to-date" är för att git kan inte skicka något till glasmontern om arkivlådan är tom.