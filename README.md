# apt-is-dumb
Apt looks very bad, your eyes will get burned while using it.

### So lets use Nala!

Add Repository
```
echo "deb http://deb.volian.org/volian/ scar main" | sudo tee /etc/apt/sources.list.d/volian-archive-scar-unstable.list
wget -qO - https://deb.volian.org/volian/scar.key | sudo tee /etc/apt/trusted.gpg.d/volian-archive-scar-unstable.gpg > /dev/null
```

Install Nala
```
sudo apt update && sudo apt install nala -y
```

Put the Alias to your bashrc

```
echo "alias apt='nala'" >> .bashrc
```

Congrats! You are ready to go! do "sudo apt update" and see how amazing it looks! 

Your eyes won't tear any more.
