# Laboratorium z administracji Active Directory

Zebrałem tutaj praktyczne laboratoria z zakresu Active Directory i Windows Server. Repozytorium dokumentuje wykonane przeze mnie konfiguracje oraz zadania administracyjne realizowane we własnym środowisku testowym.

## Środowisko

- Windows Server 2022 21H2
- Active Directory Domain Services (AD DS)
- DNS
- VirtualBox 7.2.8
- Domena: ktech.lab (Lab01)
- Kontroler domeny: DC01 (192.168.1.10)

## Laboratoria


| Lab   | Opis                                                      | Status |
| ----- | --------------------------------------------------------- | ------ |
| Lab01 | Wdrożenie Windows Server i konfiguracja kontrolera domeny | ⬜      |
| Lab02 | Projektowanie i tworzenie struktury OU                    | ⬜      |
| Lab03 | Tworzenie użytkowników i grup                             | ⬜      |
| Lab04 | Dołączenie klienta Windows 11 do domeny i test logowania  | ⬜      |
| Lab05 | Konta komputerów w Active Directory                       | ⬜      |
| Lab06 | Polityki haseł                                            | ⬜      |
| Lab07 | Group Policy (GPO)                                        | ⬜      |
| Lab08 | Udziały sieciowe i uprawnienia NTFS                       | ⬜      |
| Lab09 | Profile użytkowników i dyski sieciowe                     | ⬜      |
| Lab10 | PowerShell do zarządzania Active Directory                | ⬜      |
| Lab11 | Backup i odzyskiwanie Active Directory                    | ⬜      |
| Lab12 | Scenariusze Help Desk                                     | ⬜      |


## Struktura repozytorium

```text
active-directory-labs
│
├── lab01-active-directory-deployment
├── lab02-organizational-units
├── lab03-users-and-groups
├── lab04-domain-join-and-login
├── lab05-computer-accounts
├── lab06-password-policies
├── lab07-group-policy
├── lab08-shared-folders-and-ntfs-permissions
├── lab09-user-profiles-and-network-drives
├── lab10-powershell-for-active-directory
├── lab11-active-directory-backup-and-recovery
└── lab12-helpdesk-scenarios
```

