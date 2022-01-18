# ChatOpgave Apportsystems

## Opgave beskrivelse

Opgaven går ud på at lave et anonymt chatrum, som skal laves ved hjælp af .Net og et selvvalgt frontend teknologi.

## Krav

- [x] Skal være tilgængelig igennem en web browser
- [X] Hver tab skal repræsentere en ny brugere
- [X] Hver gang nogen sender en bedsked, skal alle brugere kunne se det
- Jeg har brugt imellem 3-4 timer på opgaven
	- Selve opgaven tog ca 40-60 min
	- Resten af tiden er blevet brugt på dokumentation, ekstra features, og at læse op på SignalR

#### Ekstra features

- [x] Brugerne har mulighed for at se hvornår en besked blev sendt
- [x] Der bliver skrevet i chatten, når en brugere deltager i chatten
- [ ] Der bliver skrevet i chatten, når en brugere forlader chatten

## Tilgang til opgaven

Jeg har valgt at benytte [Blazor](https://docs.microsoft.com/da-dk/aspnet/core/blazor/?WT.mc_id=dotnet-35129-website&view=aspnetcore-6.0), til at gennemføre opgaven. <br>
Grunden til at jeg benytter Blazor, er netop fordi det køre på .Net, og fordi den har en inbygget feature som hedder [SignalR](https://docs.microsoft.com/da-dk/aspnet/core/signalr/introduction?WT.mc_id=dotnet-35129-website&view=aspnetcore-6.0).
Det smarte ved SignalR er netop at, man kan sende en request med data, ned tilbage til serveren, hvor den så sender dataen og requesten tilbage til,
enten alle clienter, en bestemt client, eller en hel gruppe af clienter. Ikke nok med at den gør det, så opdatere dataen også med det samme, på selve applicationen.

Jeg benytter bootstrap, og CSS til styling.

## NuGet pakker
|NuGet navn|Version|
|:----------|-------|
|Microsoft.AspNetCore.SignalR.Client|5.0.13|

## Applikationer og hjælpemidler

|Applikation navn|Version|
|:----------|-------|
|Visual studio|16.11.9|
|Google Chrome|97.0.4692.71|

|Hjælpemidler|Links|
|:----------|-------|
|Microsoft SignalR|[Link](https://docs.microsoft.com/da-dk/aspnet/core/tutorials/signalr-blazor?view=aspnetcore-6.0&tabs=visual-studio&pivots=server)|
|Markdown cheatsheet|[Link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)|

<center>Kenneth Jessen</center>