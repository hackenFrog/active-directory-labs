<img width="1920" height="1042" alt="01-install-dc01" src="https://github.com/user-attachments/assets/332c7a39-439c-4770-9470-bad161985fe0" /># Lab01 - Domain Controller

## Cel

Instalacja i konfiguracja kontrolera domeny Active Directory oraz usługi DNS w środowisku VirtualBox wraz z praktyczną weryfikacją poprawności działania środowiska.

## Środowisko
Szczegóły środowiska: [README](../README.md)

## Założenia

* Instalacja Windows Server 2022.
* Konfiguracja statycznego adresu IP.
* Instalacja roli AD DS.
* Utworzenie nowego lasu i domeny.
* Weryfikacja poprawności działania usług AD DS i DNS.

## Przebieg

### 1. Pobranie obrazu ISO z oficjalnej strony producenta
Laboratorium rozpocząłem od pobrania obrazu ISO systemu Windows Server 2022 z oficjalnej strony Microsoft. Wybrałem najnowsze wersje systemów, aby pracować na aktualnym środowisku.

### 2. Tworzenie maszyny wirtualnej
Kolejnym etapem było utworzenie maszyny wirtualnej oraz instalacja systemu Windows Server 2022. Do przygotowania środowiska wykorzystałem VirtualBox. Szczegółowy proces instalacji systemu został pominięty w dokumentacji, ponieważ celem laboratorium jest konfiguracja usług AD DS i DNS.
![Instalacja Windows Server](01-install-dc01.png)




## Weryfikacja

- [x] Serwer został podniesiony do roli kontrolera domeny.
- [x] Utworzono nowy las i domenę.
- [x] Usługa DNS działa poprawnie.
- [x] Możliwe jest uruchomienie Active Directory Users and Computers.


## Napotkane problemy

| Problem | Rozwiązanie |
| ------- | ----------- |
| Niska wydajność virtualbox | -           |

## Czego się nauczyłem

* ...
* ...
* ...

