# pyswahili
A programming language to built on top of Python to easily allow swahili speakers to get started with programming without ever knowing english


**pyswahili** is not a completely independent language but more of a swahili version of **python language**, syntax and language grammer is 
equivalent to python one with only change of **keywords** from english to swahili. 


## pyswahili Transpiler
Transpiler(Pyswahili) is for converting the the swahili version of python to english version so as it can be intepreted by the python Intepreter

## extension ?

There is no official extension for pyswahili, so for now **.py** is fine.

## Repl vs Script

Similar to Python, Pyswahili supports both mode the Read-evaluate-print(**Repl**) loop and Script mode, 
Repl enable you to interactively execute pyswahili code line by line without requiring writing a complete program while on other side **Script mode** require you 
to write your Pyswahili code on a file and run it as whole.

## Getting started 

To get started using Pyswahili you might need to either **clone** or **manually download** the repository 
and then to using pip command to install the package just as shown below.

### Linux users 
It might require admistrator priveledge to install so use **sudo** during the installation.

```bash 
$ git clone https://github.com/Kalebu/pyswahili
$ sudo pip3 install -e pyswahili
```


### Window Users
If you're Window user I would recommed running command prompt(cmd) with admistrator priveledge during the installation.

```powershell
$ git clone https://github.com/Kalebu/pyswahili
$ cd pyswahili
$ pip install -e pyswahili
```

## REPL MODE
Now that that the pyswahili package is installed, now we can start playing with it, to invove repl jus run **pyswahili** without any argument 
just as shown below;

```bash
$-> pyswahili
Pyswahili 0.0.1 on Linux 
By @KalebuJordan
>>> 
```

### Usage

The Pyswahili REPL is used the same wise as the normal python repl, supporting basic statements to complex logic with block statements written in swahili, 
just as illustrated in the example below.

```python
>>> a = 12
>>> a
12
>>> a + 89
101
>>> andika('umri wako ni', a)
umri wako is 12
>>> kama a%2==0:
...     andika(a, ' ni namba shufwa')
...zaidi:
...     andika(a, ' ni namba witiri')
...
12  is andmba shufwa
```

If you're looking carefully the word *namba* changed to *andmba* this due to pyswahili accidentally replaced *na* with *and*, 
so still it's not perfect perhaps the basic feature are working properly.


## SCRIPT MODE
In script mode, you're supposed to have write your pyswahili code in a file and then pyswahili will run it as whole, 
your code should follow pyswahili syntax (python one) for it to be evaluated.

- hello.py

```python 

namba = ingiza('Namba yoyote : ')
namba = int(namba)

ikiwa no imo katiya(1, 12):
    andika(no, 'x ', namba, '=', no*namba)
```

### running script

```bash
$ pyswahili hello.py 
Namba yoyote : 8 
1 x  8 = 8
2 x  8 = 16
3 x  8 = 24
4 x  8 = 32
5 x  8 = 40
6 x  8 = 48
7 x  8 = 56
8 x  8 = 64
9 x  8 = 72
10 x  8 = 80
11 x  8 = 88
```

## SUPPORTED KEYWORDS 

If you want to see all the supported keywords by pyswahili you see all of them by viewing 
this [Pyswahili supported keywords](https://github.com/Kalebu/pyswahili/blob/main/pyswahili/Swahili/sw_to_en.py),
Keywords are not final so whenever you see a need for a keyword change feel free to reach me directly.


## To Do 

- [] Making sure only keywords are replaced 
- [] Improving documentation 
- [] 


# Give it a star 

If you found this repository useful, give it a star 

You can also keep in touch with on [Twitter](https://twitter.com/j_kalebu).


## Bug bounty?

If you encounter **issue** with the usage of the package, feel free raise an **issue** so as 
we can fix it as soon as possible(ASAP) or just reach me directly through [email](isaackeinstein@gmail.com)


*The journey has just began*