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
