STEAM (2024-05)
<br/>
Velikost 128MB https://drive.google.com/drive/folders/1lUzTWyFtGd--2wp6W81oRYTc6Ht0QgXD

Chyby
<br/>
-pokud je systém zabezpečený a proces "DiRT.exe" se nemůže připojit na internet, tak bude likvidovat systémové úložiště (zahltí+zpomalí systém konstantní operací "TCP Disconnect" a hlavně zápisem na SSD rychlostí 5,5 MB/s = 20GB za hodinu). Hra tím trpí odjakživa (WinXP+7) a je jedno zda se jedná o Steam EXE nebo 3 různé cracky verze 1.2. Ten nejjednodušší lék je ve správci zařízení zakázat síťovou kartu (pokus o zapnutí síťové karty při hraní zřejmě skončí pádem systému). Příklad zapnutí/vypnutí karty maximálně jednou klávesou/klikem (v případě použití Autohotkey ani to ne)
```
C:\devmanview\DevManView.exe /disable "Realtek PCIe GbE Family Controller"
C:\devmanview\DevManView.exe /enable "Realtek PCIe GbE Family Controller"
```

-rozmazávací snový opar se může vypnout odstraněním ```type``` souborů ve složce ```postprocess```
