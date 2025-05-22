# Řízení bateriového úložiště pomocí PLC společnosti AMiT

Tento repozitář obsahuje vývojový projekt vytvořený v prostředí **DetStudio**, který slouží jako implementace řídicího systému bateriového úložiště v rámci diplomové práce na VUT v Brně.

## Popis projektu

Projekt je zaměřen na návrh a realizaci robustního a rozšiřitelného systému řízení akumulačního systému s využitím **PLC jednotky společnosti AMiT**. Součástí implementace je:

- komunikace s BMS a střídačem přes **Modbus TCP**,
- zpracování dat do strukturované podoby a jejich mapování do procesu,
- implementace algoritmů pro řízení provozu s ohledem na životnost **LiFePO₄ článků**,
- návrh unifikované struktury pro stavová a chybová hlášení („virtuální baterie“),

Řešení bylo testováno v reálných podmínkách ve společnosti  **ECM Systems Solutions**.


## Požadavky

- DetStudio 
- PLC AMiNi5D (nebo jiný AMiT kompatibilní)  
- zařízení komunikující přes Modbus TCP (Pylontech, REFU)

## Diplomová práce

Tento projekt je součástí diplomové práce, která je veřejně dostupná:

**Bibliografická citace:**  
HULA, Jiří. *Řízení bateriového úložiště pomocí PLC společnosti AMiT.* Brno, 2025. Dostupné také z:  
[https://www.vut.cz/studenti/zav-prace/detail/165768]  
Diplomová práce. Vysoké učení technické v Brně, Fakulta strojního inženýrství, Ústav automatizace a informatiky.  
Vedoucí práce: Ing. et Ing. Stanislav Lang, Ph.D.

## Licence

Tento software je šířen pod licencí **GNU General Public License v3.0**.  
Podmínky použití naleznete v souboru [`LICENSE`](./LICENSE) nebo na stránkách [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html).
