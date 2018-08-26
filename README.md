# plata o plomo
Plata O Plomo (Spanish: Silver or Lead) is a term used in Latin America for when someone is forced to accept a bribe.

He or she can either accept the bribe or get a lead bullet in the head.

This repository contains minor bugs and vulnerabilities that I found in iOS userland.

## CVE 2018-???? iBooks Type Confusion
A type confusion vulnerability in iBooks may lead to memory corruption.
An attacker with access to a paired device over usb can exploit this vulnerability to cause a persistant denial of service in the iBooks application.
An attacker may be able to corrupt memory in the iBooks application.
The issue can be fixed by improved serialization and sandboxing.

## CVE 2018-???? MobileSlideShow Type Confusion
A type confusion vulnerability in MobileSlideShow may lead to memory corruption.
The issue can be fixed by improved serialization.

## CVE 2018-???? Launchd Type Confusion
A type confusion vulnerability exists in the initialization of launchdaemons.
A local attacker may be able to execute arbitrary code with system privileges and persistancy.
The issue can be fixed by improved serialization.

## CVE-2018-???? libsqlite3 Infoleak
A vulnerability exists in libsqlite3.
This is a known vulnerability but Apple has not patched it yet.
An attacker may be able to leak information about the address space of applications using the sqlite3 library.

## CVE-2018-???? libsqlite3 Memory Corruption
A vulnerability exists in libsqlite3.
This is a known vulnerability but Apple has not patched it yet.
An attacker may be able to execute arbitrary code with system privileges in applications using the sqlite3 library.
