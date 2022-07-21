# Multiple Instance Learning

*This repository holds all the necessary code to run the very-same experiments described in the paper "".*

---

## References

If you use our work to fulfill any of your needs, please cite us:

```

```

---

## Structure


---

## Package Guidelines

### Installation

Install all the pre-needed requirements using:

```Python
pip install -r requirements.txt
```

Install Optimum-Path Forest library as following:

```
git clone https://github.com/jppbsi/libopf
cd LibOPF
make
gcc -Wl,-soname,OPF -o OPF.so -shared -fPIC src/OPF.c src/util/common.c src/util/gqueue.c src/util/realheap.c src/util/set.c src/util/sgctree.c src/util/subgraph.c -I include/ -I include/util/
```

go to your home directory, open .bashrc (Linux) or .bash_profile (OSX) and add the following line:

```
export OPF_DIR=<path where LibOPF has been installed>
```

## Usage



---

## Support

We know that we do our best, but it is inevitable to acknowledge that we make mistakes. If you ever need to report a bug, report a problem, talk to us, please do so! We will be available at our bests at this repository or d.rodrigues@unesp.br.

---
