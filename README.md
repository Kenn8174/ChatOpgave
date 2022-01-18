# ChatOpgave Apportsystems

## Opgave beskrivelse

Opgaven g�r ud p� at lave et anonymt chatrum, som skal laves ved hj�lp af .Net og et selvvalgt frontend teknologi.

## Krav

- [x] Skal v�re tilg�ngelig igennem en web browser
- [X] Hver tab skal repr�sentere en ny brugere
- [X] Hver gang nogen sender en bedsked, skal alle brugere kunne se det
- Jeg har brugt imellem 3-4 timer p� opgaven
	- Selve opgaven tog ca 40-60 min
	- Resten af tiden er blevet brugt p� dokumentation, ekstra features, og at l�se op p� SignalR

#### Ekstra features

- [x] Brugerne har mulighed for at se hvorn�r en besked blev sendt
- [x] Der bliver skrevet i chatten, n�r en brugere deltager i chatten
- [ ] Der bliver skrevet i chatten, n�r en brugere forlader chatten

## Tilgang til opgaven

Jeg har valgt at benytte [Blazor](https://docs.microsoft.com/da-dk/aspnet/core/blazor/?WT.mc_id=dotnet-35129-website&view=aspnetcore-6.0), til at gennemf�re opgaven. <br>
Grunden til at jeg benytter Blazor, er netop fordi det k�re p� .Net, og fordi den har en inbygget feature som hedder [SignalR](https://docs.microsoft.com/da-dk/aspnet/core/signalr/introduction?WT.mc_id=dotnet-35129-website&view=aspnetcore-6.0).
Det smarte ved SignalR er netop at, man kan sende en request med data, ned tilbage til serveren, hvor den s� sender dataen og requesten tilbage til,
enten alle clienter, en bestemt client, eller en hel gruppe af clienter. Ikke nok med at den g�r det, s� opdatere dataen ogs� med det samme, p� selve applicationen.

Jeg benytter bootstrap, og CSS til styling.

## NuGet pakker
|NuGet navn|Version|
|:----------|-------|
|Microsoft.AspNetCore.SignalR.Client|5.0.13|

## Applikationer og hj�lpemidler

|Applikation navn|Version|
|:----------|-------|
|Visual studio|16.11.9|
|Google Chrome|97.0.4692.71|

|Hj�lpemidler|Links|
|:----------|-------|
|Microsoft SignalR|[Link](https://docs.microsoft.com/da-dk/aspnet/core/tutorials/signalr-blazor?view=aspnetcore-6.0&tabs=visual-studio&pivots=server)|
|Markdown cheatsheet|[Link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)|

<center>Kenneth Jessen</center>