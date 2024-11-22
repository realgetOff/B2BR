
<p align="center">
  <img src="https://github.com/realgetOff/main/blob/main/Header/Header%20B2BR.png">
</p>

<p align="center">
	<img src="https://img.shields.io/badge/status-finished-chocolate"/>
	<img src="https://img.shields.io/badge/evaluated-22%20%2F%2011%20%2F%202024-chocolate"/>
	<img src="https://img.shields.io/badge/score-100%2F100-chocolate"/>
	<img src="https://img.shields.io/badge/language-SHELL_100%25-chocolate"/>
	<img src="https://img.shields.io/badge/last_commit-november-chocolate"/>
	<a href='https://profile.intra.42.fr/users/mforest-' target="_blank"><img alt='42' src='https://img.shields.io/badge/Intra-100000?style=flat-round&logo=42&logoColor=white&labelColor=000000&color=000000'/></a>
</p>

<p align="center">
	<a href="#about">About</a> •
	<a href="#mandatory">Mandatory</a> •
	<a href="#bonus">Bonus</a> •
	<a href="#norminette">Norminette</a> •
	<a href="#contributing">Contributing</a> •
	<a href="#license">License</a>
</p>

## ABOUT
This system administration project focuses on setting up a secure virtual machine. It covers key topics such as virtualization, partitioning, LVM, command-line tools, SSH, and system security measures like sudo, firewalls, and password policies. The project repository includes a script for automated tasks and the virtual machine signature.

- [Subject](https://github.com/realgetOff/B2BR/blob/main/fr_b2br_subject.pdf) `PDF`
- [References](https://github.com/realgetOff/B2BR/tree/main) `GitHub`

## MANDATORY
> During the evaluation, I was asked questions about the topics below;
- [x] Choose between two Linux-based operating systems: `Rocky` or `Debian`;
- [x] Create at least 2 encrypted partitions using `LVM`;
- [x] Ensure `SSH services` are running on specific ports;
- [x] Configure a `UFW firewall` and leave only port `4242` open;
- [x] Set up the `hostname` (will be changed during evaluation) and a strong `password policy` for all users;
- [x] Set up a strong `sudo` configuration;
- [x] Create a `monitoring script` that displays specific information every 10 minutes at server startup;

## BONUS
> During the evaluation, also had to justify my choices;
- [ ] Set up a different partition structure;
- [ ] Set up a functional `WordPress` website with the following services: `lighttpd`, `MariaDB` and `PHP`;
- [ ] Set up a service of my own choice that I think is useful (I recommend fail2ban, which prevents bruteforce attacks);

## NORMINETTE
> At 42 School, it is expected that almost every project is written following the Norm, which is the coding standard of the school.

```
- No for, do...while, switch, case, goto, ternary operators, or variable-length arrays allowed;
- Each function must be a maximum of 25 lines, not counting the function's curly brackets;
- Each line must be at most 80 columns wide, with comments included;
- A function can take 4 named parameters maximum;
- No assigns and declarations in the same line (unless static);
- You can't declare more than 5 variables per function;
- ...
```

* [42 Norms](https://github.com/42School/norminette/blob/master/pdf/en.norm.pdf) - Information about 42 code norms. `PDF`
* [Norminette](https://github.com/42School/norminette) - Tool to respect the code norm, made by 42. `GitHub`
* [42 Header](https://github.com/42Paris/42header) - 42 header for Vim. `GitHub`

## CONTRIBUTING

If you find any issues or have suggestions for improvements, feel free to fork the repository and open an issue or submit a pull request. All credit goes to @jotavare (for the README.md).
