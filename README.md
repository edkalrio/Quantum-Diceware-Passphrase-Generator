![xkcd password strength](http://imgs.xkcd.com/comics/password_strength.png)
# Quantum Diceware Passphrase Generator
DIQ is a quantum random passphrase generator based on the Australian National University Quantum Random Generator. It emulates the diceware method in a binary approach (like a coin toss) to generate a 78 bits of entropy passphrase, by measuring the quantum fluctuations of the electromagnetic field of the vacuum.

The word list in `dicewds8k[]` is based on [dicewds8k.txt](http://world.std.com/~reinhold/diceware8k.txt) by Arnold G. Reinhold.

DIQ is the easiest and safest way to get a strong passphrase, as long as you trust on the TLS 1.0 connection with the server.
### Installation
		git clone https://github.com/edkalrio/Quantum-Diceware-Passphrase-Generator.git
		cp ~/Quantum-Diceware-Passphrase-Generator/diq.sh /usr/bin/diq
		sudo chmod +x /usr/bin/diq
### Execution
  		diq
### UNIX Checklist
- DIQ does one thing and does it well ☑
- DIQ works among other software ☑
- DIQ handles text streams ☑
