
# Lost cities

Instrukcja konfiguracji serwera i klienta dla gry sieciowej Minecraft.

## Obecna wersja

- Minecraft 1.20.1
- [Forge 1.20.1-47.1.43](https://files.minecraftforge.net/net/minecraftforge/forge/) (wersja wyznaczona przez OptiFine)
- [OptiFine HD U I6 pre6](https://www.optifine.net/downloads) (ostatnia dla 1.20.1)

## Instalacja klienta

W systemie Windows przejdź do katalogu:

```
C:\Users\<użytkownik>\AppData\Roaming
```

W systemie macOS przejdź do katalogu:

```
/Users/<użytkownik>/Library/Application Support
```

Następnie wykonaj kroki:

1. Skopiuj katalog `.minecraft` i nazwij go `.minecraft-cherry`
2. Uruchom instalator **Forge** i zainstaluj klienta w katalogu `.minecraft`, żeby launcher wiedział o istnieniu takiego silnika
3. Uruchom instalator **Forge** i zainstaluj klienta w katalogu `.minecraft-cherry`, ponieważ tam będziemy trzymać mody dla naszego serwera odseparowane od innych wersji
4. Wklej mody z katalogu [minecraft-1.20.1/mods](./minecraft-1.20.1/mods) do katalogu `.minecraft-cherry/mods`
5. Wklej mody z katalogu [minecraft-1.20.1/mods-client](./minecraft-1.20.1/mods-client) do katalogu `.minecraft-cherry/mods`
6. Wklej shader-y z katalogu [shaderpacks](./shaderpacks) do katalogu `.minecraft-cherry/shaderpacks`
7. Uruchom **Launcher** gry i utwórz instalację:
    * Idź do zakładki **Instalacje**
    * Kliknij **Nowa instalacja**
    * Wybierz ikonę pomarańczowego piaskowca (bo nie ma nic wiśniowego na liście)
    * Nazwij instalację `Mods Cherry`
    * Katalog gry znajdź przez przycisk **Przeglądaj** i wybierz `.minecraft-cherry`
    * Zakończ klikają **Stwórz**

Po zakończeniu powinieneś mieć utworzoną następującą instalację:

![Instalacja Mods Cherry](./minecraft-1.20.1/instalacja.png)

## Uruchamianie gry

Wykonaj następujące kroki:

1. Uruchom **Launcher**
2. Przejdź do zakładki **Graj**
3. Wybierz z listy instalację `Mods Cherry`
4. Kliknij **Graj**

W uruchomionej grze:

1. Przejdź do **trybu wieloosobowego**
2. Dodaj serwer o nazwie `Lost Cities`
3. Użyj poufnego adresu IP serwera i kliknij **Gotowe**
4. Połącz się z serwerem

Wybierz shader:

1. Ustawienia
2. Ustawienia graficzne
3. Shader-y
4. Wybierz ulubiony z listy

## Lista modów

| Curseforge                                                                                                      | Plik                                                                                                                       | Opis                               | Uwagi                                                                                |
|-----------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|------------------------------------|--------------------------------------------------------------------------------------|
| [Advanced Netherite](https://www.curseforge.com/minecraft/mc-mods/advanced-netherite)                           | [advancednetherite-forge-2.0.2-1.20.1.jar](./minecraft-1.20.1/mods/advancednetherite-forge-2.0.2-1.20.1.jar)               | Dodatkowe kolory zbroi             |                                                                                      |
| [AI Improvements](https://www.curseforge.com/minecraft/mc-mods/ai-improvements)                                 | [AI-Improvements-1.20-0.5.2.jar](./minecraft-1.20.1/mods/AI-Improvements-1.20-0.5.2.jar)                                   | Inteligentne moby                  |                                                                                      |
| [AttributeFix](https://www.curseforge.com/minecraft/mc-mods/attributefix)                                       | [AttributeFix-Forge-1.20.1-21.0.2.jar](./minecraft-1.20.1/mods/AttributeFix-Forge-1.20.1-21.0.2.jar)                       | Ma wpływ na limity                 |                                                                                      |
| [Backpacked](https://www.curseforge.com/minecraft/mc-mods/backpacked)                                           | [backpacked-forge-1.20.1-2.2.5.jar](./minecraft-1.20.1/mods/backpacked-forge-1.20.1-2.2.5.jar)                             | Plecak z królików                  | Wymaga [Framework](https://www.curseforge.com/minecraft/mc-mods/framework)           |
| [Balm](https://www.curseforge.com/minecraft/mc-mods/balm)                                                       | [balm-forge-1.20.1-7.1.4.jar](./minecraft-1.20.1/mods/balm-forge-1.20.1-7.1.4.jar)                                         | Biblioteka dla modów               |                                                                                      |
| [Bookshelf](https://www.curseforge.com/minecraft/mc-mods/bookshelf)                                             | [Bookshelf-Forge-1.20.1-20.1.6.jar](./minecraft-1.20.1/mods/Bookshelf-Forge-1.20.1-20.1.6.jar)                             | Biblioteka dla modów               |                                                                                      |
| [Carry On](https://www.curseforge.com/minecraft/mc-mods/carry-on)                                               | [carryon-forge-1.20.1-2.1.2.7.jar](./minecraft-1.20.1/mods/carryon-forge-1.20.1-2.1.2.7.jar)                               | Pozwala przenosić rzeczy           |                                                                                      |
| [Claim Chunk](https://www.curseforge.com/minecraft/mc-mods/claim-chunk)                                         | [ClaimChunk-1.20-1.0.17.jar](./minecraft-1.20.1/mods/ClaimChunk-1.20-1.0.17.jar)                                           | Rezerwuje chunk                    |                                                                                      |
| [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps)                                                   | [Clumps-forge-1.20.1-12.0.0.3.jar](./minecraft-1.20.1/mods/Clumps-forge-1.20.1-12.0.0.3.jar)                               | Grupuje kule doświadczenia         | Podnosi wydajność, od 1.17 wymagany tylko na serwerze                                |
| [Collective](https://www.curseforge.com/minecraft/mc-mods/collective)                                           | [collective-1.20.1-6.66.jar](./minecraft-1.20.1/mods/collective-1.20.1-6.66.jar)                                           | Biblioteka dla modów               |                                                                                      |
| [Comforts](https://www.curseforge.com/minecraft/mc-mods/comforts)                                               | [comforts-forge-6.3.4+1.20.1.jar](./minecraft-1.20.1/mods/comforts-forge-6.3.4+1.20.1.jar)                                 | Dodaje hamaki i materace           |                                                                                      |
| [CustomSkinLoader](https://www.curseforge.com/minecraft/mc-mods/customskinloader)                               | [CustomSkinLoader_ForgeActive-14.18.1.jar](./minecraft-1.20.1/mods/CustomSkinLoader_ForgeActive-14.18.1.jar)               | Ładuje skórki dla graczy           |                                                                                      |
| [DEUF - Duplicate Entity UUID Fix](https://www.curseforge.com/minecraft/mc-mods/deuf-duplicate-entity-uuid-fix) | [deuf-1.20.1-1.3.jar](./minecraft-1.20.1/mods/deuf-1.20.1-1.3.jar)                                                         | Wycisza logi dla popularnego błędu |                                                                                      |
| [Double Doors](https://www.curseforge.com/minecraft/mc-mods/double-doors)                                       | [doubledoors-1.20.1-5.0.jar](./minecraft-1.20.1/mods/doubledoors-1.20.1-5.0.jar)                                           | Otwiera drzwi w parach             | Trzeba zmniejszyć zasięg w configu                                                   |
| [Ecologics](https://www.curseforge.com/minecraft/mc-mods/ecologics)                                             | [ecologics-forge-1.20.1-2.2.0.jar](./minecraft-1.20.1/mods/ecologics-forge-1.20.1-2.2.0.jar)                               | Dodaje biomy, zwierzęta i rośliny  |                                                                                      |
| [Enchantment Descriptions](https://www.curseforge.com/minecraft/mc-mods/enchantment-descriptions)               | [EnchantmentDescriptions-Forge-1.20.1-17.0.8.jar](./minecraft-1.20.1/mods/EnchantmentDescriptions-Forge-1.20.1-17.0.8.jar) | Opisy do ulepszeń                  |                                                                                      |
| [Framework](https://www.curseforge.com/minecraft/mc-mods/framework)                                             | [framework-forge-1.20.1-0.6.16.jar](./minecraft-1.20.1/mods/framework-forge-1.20.1-0.6.16.jar)                             | Biblioteka dla modów               | Wymagany przez [Backpacked](https://www.curseforge.com/minecraft/mc-mods/backpacked) |
| [Guard Villagers](https://www.curseforge.com/minecraft/mc-mods/guard-villagers)                                 | [guardvillagers-1.20.1-1.6.3.jar](./minecraft-1.20.1/mods/guardvillagers-1.20.1-1.6.3.jar)                                 | Wojownicy we wioskach              |                                                                                      |
| [Lost Cities](https://www.curseforge.com/minecraft/mc-mods/lost-cities-survive-the-dead-edition)                | [lostcities-1.20-7.0.3.jar](./minecraft-1.20.1/mods/lostcities-1.20-7.0.3.jar)                                             | Struktury miast                    | To nasz gwóźdź programu                                                              |
| [Open Parties and Claims](https://www.curseforge.com/minecraft/mc-mods/open-parties-and-claims)                 | [open-parties-and-claims-forge-1.20.1-0.20.1.jar](./minecraft-1.20.1/mods/open-parties-and-claims-forge-1.20.1-0.20.1.jar) | Rezerwuje teren i tworzy partie    | Też dość istotne                                                                     |
| [Serene Seasons](https://www.curseforge.com/minecraft/mc-mods/serene-seasons)                                   | [SereneSeasons-1.20.1-9.0.0.46.jar](./minecraft-1.20.1/mods/SereneSeasons-1.20.1-9.0.0.46.jar)                             | Pory roku                          | Śnieg i zima czasem denerwują                                                        |
| [Sit](https://www.curseforge.com/minecraft/mc-mods/sit)                                                         | [sit-1.20-1.3.3.jar](./minecraft-1.20.1/mods/sit-1.20-1.3.3.jar)                                                           | Można usiąść na schodku            |                                                                                      |
| [Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap)                                  | [Xaeros_Minimap_23.8.3_Forge_1.20.jar](./minecraft-1.20.1/mods/Xaeros_Minimap_23.8.3_Forge_1.20.jar)                       | Minimapa                           |                                                                                      |
| [Xaero's World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map)                              | [XaerosWorldMap_1.35.0_Forge_1.20.jar](./minecraft-1.20.1/mods/XaerosWorldMap_1.35.0_Forge_1.20.jar)                       | Mapa świata                        |                                                                                      |
| [XP Tome](https://www.curseforge.com/minecraft/mc-mods/xp-tome)                                                 | [xptome-1.20.1-2.1.8.jar](./minecraft-1.20.1/mods/xptome-1.20.1-2.1.8.jar)                                                 | Można schować XP do książki        |                                                                                      |

Łącznie 25 modów dla klienta i serwera, które muszą być takie same dla obu.

## Lista modów tylko po stronie klienta

| Curseforge                                     | Plik                                                                                                                | Opis               | Uwagi                          |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|--------------------|--------------------------------|
| [OptiFine](https://www.optifine.net/downloads) | [preview_OptiFine_1.20.1_HD_U_I6_pre6.jar](./minecraft-1.20.1/mods-client/preview_OptiFine_1.20.1_HD_U_I6_pre6.jar) | Obsługuje shader-y | Wymaga konkretnej wersji Forge |

Jeden mod tylko dla klienta. Łącznie 26 wszystkich.

## Rozwiązywanie problemów z OptiFine

### Błąd OpenGL: 1282 (Invalid Operation)

Przy używaniu shader-ów, a zwłaszcza [shaderpacks/ComplementaryShaders_v4.7.1.zip](./shaderpacks/ComplementaryShaders_v4.7.1.zip)
na ekranie czasami pokazuje się komunikat:

```
Błąd OpenGL: 1282 (Invalid Operation)
```

Jedyne co możemy zrobić to wyciszyć ten błąd:

1. Ustawienia
2. Ustawienia graficzne
3. Inne
4. Pokazuj błędy GL: `Wył`

### Brak tekstur wypełniony jednolitym kolorem

To może występować tylko dla niektórych komputerów, prawdopodobnie tylko dla macOS.
Problem rozwiązujemy następująco:

1. Po każdorazowym uruchomieniu gry przechodzimy do ustawień
2. Ustawienia graficzne
3. Jakość
4. Wyłączamy **łączone tekstury**
5. Włączamy **łączone tekstury** ponownie

Dzięki temu wszystko znów wygląda dobrze. Błąd został zgłoszony:
https://github.com/sp614x/optifine/issues/7578
