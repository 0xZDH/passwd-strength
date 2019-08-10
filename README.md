# passwd-strength

## Usage
`python passwd-strength.py <Cracking Speed (in hashes/second)>`

```
$ python passwd-strength.py

** Basic Password Strength Evaluation **
Based on password cracking at: 20,000 MH/s.

Enter Password:

[+] Password length:          8

[+] Uppercase characters:     1
[+] Lowercase characters:     7
[+] Numbers:                  -
[+] Special characters:       -

[+] Password entropy:         52

[+] Time to crack password: 0.74 hours
```

```
$ python passwd-strength.py 40000000000

** Basic Password Strength Evaluation **
Based on password cracking at: 40,000 MH/s.

Enter Password: 

[+] Password length:          8

[+] Uppercase characters:     1
[+] Lowercase characters:     7
[+] Numbers:                  -
[+] Special characters:       -

[+] Password entropy:         52

[+] Time to crack password: 0.37 hours
```
