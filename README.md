# INF563 - Final Project
**IMPORTANT NOTE: Fully functional BWT Transformation located in branch [bwt_transformation](https://github.com/jetlime/X-INF563/tree/btw_transformation)**

C implementation of the source coding with the Burrows-Wheeler transformer. A generally better source coding than Zempel-Ziv is many cases
it is used in *bzip2* for instance.

## Usage

- Compilation

```bash
make
```

- Run

    - Fill *input.txt* with the text you would like to compress.
    - Execute program
    ```bash
    ./program.exe
    ```
    - Compressed output will be in *output.txt*

## References
- [The article of Burrows Wheeler](https://www.hpl.hp.com/techreports/Compaq-DEC/SRC-RR-124.pdf)
- [An article about this article](https://marknelson.us/posts/1996/09/01/bwt.html)
- [An academic Ressource about Burrow Wheeler](http://pages.di.unipi.it/ferragina/dott2014/bwt.pdf)

## Authors

- Paul Houssel: Compression Tranformation and Inverse, Pipeline Integration
- Silviu-Andrei Maftei:, Arithmetic Encoding
- Elouan Gros: Move-to-front Encoding & Decoding, Pipeline integration
