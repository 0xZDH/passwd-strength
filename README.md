# passwd-strength

The script has a default cracking speed of 20,000 MH/s. This baseline is based on the following cracking configuration:

* 8x NVIDIA GTX 1080 Ti GPUs
* Hashtype: NTLMv2

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
