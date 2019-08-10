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
[+] Lowercase characters:     5
[+] Numbers:                  1
[+] Special characters:       1

[+] Password entropy:         95

[+] Time to crack password:   3.84 days
```

```
$ python passwd-strength.py 40000000000

** Basic Password Strength Evaluation **
Based on password cracking at: 40,000 MH/s.

Enter Password: 

[+] Password length:          8

[+] Uppercase characters:     1
[+] Lowercase characters:     5
[+] Numbers:                  1
[+] Special characters:       1

[+] Password entropy:         95

[+] Time to crack password:   1.92 days
```
