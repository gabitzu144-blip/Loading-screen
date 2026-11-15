# MoonCity Plus (Forge 1.20.1)

Mod addon: loading screen MOON, MDT, magazin cu rafturi, joburi, legatura cu MrCrayfish Vehicle.
Nu modifica mooncity / mooncityvehicles; le citeste (cash/bank) si adauga butoane in meniul K.

## Build
1. JDK 17 + internet.
2. `gradle wrapper` (o data) apoi `./gradlew build`  -> `build/libs/mooncityplus-1.20.1-1.0.0.jar`
3. Pune jar-ul in `mods/` (server + client), langa mooncity, vehicle, mooncityvehicles.
   (sau deschide folderul in IntelliJ si ruleaza `genIntellijRuns`)

## Folosire
- Meniul K: butoane noi stanga-sus (MDT, Job Center, Vehicul, Casa).
- Comenzi: /mdt, /joburi, /vehiculmeniu. Item: Tableta MDT.
- Magazin: pune `Raft Magazin`, ține item-ul in mana + SHIFT + click-dreapta (OP) ca sa-l setezi,
  `/shop price <suma>` uitandu-te la raft. Jucatorii dau click-dreapta pe raft (iau in cos) si platesc la `Casa de Marcat`.
- Joburi: Padurar/Miner/Pescar/Fermier platesc automat; Electrician: click pe `Panou Electric`.
- Vehicul: benzina, motor (Iron..Netherite), roti, culoare. Merge la orice vehicul MrCrayfish/Moonvehicles.
