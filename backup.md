backup / schachteli

Problem:
PC sollen spezielle images aufgesetzt bekommen. Es soll ein master pc aufgesetzt werden, welcher auf andere pc's kopiert werden soll.

Zusatz:
Es soll eine diff gemacht werden das extern gespeichert wird.

Ansatz:
Rdiff, rsynch + diff

Ansatz ZFS:
ZFS ist eine gute grundlage fuer ein Filesystem, chechsumming bringt gewissheit das sich die Dateien nicht veraendern.
