# BrahmAstra--BEST SPIDING TOOL EVER MADE FOR BUG BOUNTY!🔴🔴🔴🔴✔
# LOVE YOU 3000!❤ :--> CAN ENUMERATE SOO MUCH LINK FOR YOU ! AND WAY TOO MUCH !...
<p align="center">
  <img src="https://thumbs.gfycat.com/VerifiableSelfishAtlanticblackgoby-size_restricted.gif">
  </p>
<p align="center">
  <img src="https://img.shields.io/badge/Version-2.0-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/alexbieber/BrahmAstra?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/alexbieber/BrahmAstra?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/alexbieber/BrahmAstra?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/alexbieber/BrahmAstra?color=teal&style=for-the-badge">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Author-Alex--Bieber-cyan?style=flat-square">
  <img src="https://img.shields.io/badge/Open%20Source-Yes-cyan?style=flat-square">
  <img src="https://img.shields.io/badge/Written%20In-Bash-cyan?style=flat-square">
</p>
# YOUR REACTION AFETR USING THIS TOOL :-->
<p align="center">
  <img src="https://c.tenor.com/0Ll8B73iS30AAAAd/girl-shocked.gif">
  </p>

  

## BrahmaSpider : Parameter miner for humans --- Enjoy✔

![BrahmaSpider](https://raw.githubusercontent.com/alexbieber/BrahAstra/master/static/banner.PNG)

### Important Features :

  

- Finds parameters from web archives of the entered domain.

- Finds parameters from subdomains as well.

- Gives support to exclude urls with specific extensions.

- Saves the output result in a nice and clean manner.

- It mines the parameters from web archives (without interacting with the target host)

  

### Usage instructions :


# Note : Use python 3.7+
```
$ git clone https://github.com/alexbieber/BrahmAstra
```
```
$ cd BrahmAstra
```
```
$ pip3 install -r requirements.txt
```
```
$ python3 brahmastra.py --domain xyz.com
```

  

### Usage options :

```
1 - For a simple scan [without the --exclude parameter]
$ python3 brahmastra.py --domain xyz.com
-> Output ex : https://xyz.com/test.php?q=FUZZ

2 - For excluding urls with specific extensions
$ python3 brahmastra.py --domain xyz.com --exclude php,jpg,svg

3 - For finding nested parameters --->
$ python3 brahmastra.py --domain hackerone.com --level high
-> Output ex : https://xyz.com/test.php?p=test&q=FUZZ

4 - Saving the results as txt file -->
$ python3 brahmastra.py --domain xyz.com --exclude php,jpg --output xyz.txt

5 - Using with a custom placeholder text (default is FUZZ), e.g. don't add a placeholder
$ python3 brahmastra.py --domain xyz.com --placeholder FUZZ2

6 - Using the quiet mode (without printing the URLs on screen)
$ python3 brahmastra.py --domain xyz.com --quiet

7 - Exclude subdomains [for parameters from domain+subdomains, do not specify this argument]
$ python3 brahmastra.py --domain xyz.com --subs False 
```

### BrahmaSpider + TomNomNom 'GF' (for massive pwnage)

  

Lets say you have already installed BrahmaAstra and now you want to filter out the juicy parameters from plethora of parameters. No worries you can easily do it using [GF(by tomnomnom)](https://github.com/tomnomnom/gf) .

  

**Note** : Make sure you have [go](https://golang.org/doc/install) properly installed on your machine .

  

**Follow along this :**

```
$ go get -u github.com/tomnomnom/gf
$ cp -r $GOPATH/src/github.com/tomnomnom/gf/examples ~/.gf

Note : Replace '/User/levi/go/bin/gf' with the path where gf binary is located in your system.

$ alias gf='/User/levi/go/bin/gf'
$ cd ~/.gf/

Note : Paste JSON files(https://github.com/alexbieber/BrahmaAstra/tree/master/gf_profiles) in ~/.gf/ folder

Now run BrahmaAstra and navigate to the output directory

$ gf redirect domain.txt //for potential open redirect/SSRF parameters
$ gf xss domain.txt //for potential xss vulnerable parameters
$ gf potential domain.txt //for xss + ssrf + open redirect parameters
$ gf wordpress domain.txt //for wordpress urls

[More GF profiles to be added soon!]
```

  

## Example :

```
$ python3 brahmastra.py --domain loveyou3000.com --exclude woff,css,js,png,svg,php,jpg --output loveyou3000.txt
```

  



#### Note :

```
As it fetches the parameters from web archive data ,
so chances of false positives are high.
```

### Contributing to BrahmAstra :

 - Report bugs , missing best practices 
 - Shoot my [DM](https://twitter.com/alexbieber12341) with new ideas 
 - Make more GF profiles (.json files)
 - Help in Fixing bugs
 - Submit Pull requests 

 
  

### My Twitter :


**Say Hyy** : [alexbieber12341](https://twitter.com/alexbieber12341)

  

