# gestion-etudiants

Student management program in C, using a singly linked list.
Output is displayed in blue using ANSI color codes.

## Features

- Add a student (ID, name, average)
- Display the list of all students
- Search for a student by ID
- Display students whose average is above 10

## Compile and run

```bash
gcc main.c -o etudiants
./etudiants
```

## Menu

```
(1) ajouter un etudiant
(2) afficher la liste des etudiants
(3) chercher un etudiant
(4) afficher les etudiants a moyenne plus que 10
```

Type the number of the option you want, then follow the instructions.
To quit, enter any number other than 1 to 4 (for example `0`).

## Example

```
ID : 1
NOM : Sara
MOYENNE : 14.5
```

Then option 2 displays:

```
[Etudiant 1] id : 1      nom : Sara      moyenne : 14.50
```
