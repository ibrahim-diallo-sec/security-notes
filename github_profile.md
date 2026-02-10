# Profil GitHub : ibrahim-diallo-sec

## Informations du profil

- **Username** : `ibrahim-diallo-sec`
- **Nom affiché** : `Ibrahim Diallo`
- **Bio** : `Security researcher @ TechShield Solutions CI, Abidjan | Pentest | CTF Player`
- **Location** : `Abidjan, Côte d'Ivoire`
- **Website** : (laisser vide)

## Repo à créer : `security-notes`

Créer un repo public `security-notes` avec les fichiers suivants :

### README.md

```markdown
# Security Notes

Notes personnelles et ressources en cybersécurité.

## Contenu

- `bookmarks.md` - Liens et ressources utiles
- `cheatsheet.md` - Aide-mémoire pentest

## Contact

ibrahim.diallo@techshield-ci.com
```

### cheatsheet.md

```markdown
# Cheatsheet Pentest

## Reconnaissance

```bash
nmap -sV -sC target
nikto -h target
gobuster dir -u target -w wordlist.txt
```

## Web

```bash
sqlmap -u "target?id=1" --dbs
wfuzz -c -w wordlist.txt target/FUZZ
```

## Privilege Escalation

```bash
sudo -l
find / -perm -4000 2>/dev/null
```
```

### bookmarks.md

**IMPORTANT** : Ce fichier contient le lien vers le Gist avec le message ROT13.

```markdown
# Bookmarks

## Outils

- [CyberChef](https://gchq.github.io/CyberChef/)
- [GTFOBins](https://gtfobins.github.io/)
- [HackTricks](https://book.hacktricks.xyz/)

## CTF

- [CTFTime](https://ctftime.org/)
- [PicoCTF](https://picoctf.org/)

## Mes notes privées

- [Notes de recherche](https://gist.github.com/ibrahim-diallo-sec/e4cdb3b511336954c207830727c1955e)
```
