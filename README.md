# worder

Informação:ele pega uma lista(--input) e cria variações das palavras dentro da lista de acordo com as configurações e permutações selecionadas e colocando todas em um arquivo de saída(--output)

usage: wordlister.py [-h] --input INPUT --perm PERM --min MIN --max MAX
                     [--test TEST] [--cores CORES] [--leet] [--cap] [--up]
                     [--append APPEND] [--prepend PREPEND]

A simple wordlist generator and mangler written in python.

optional arguments:
  -h, --help         show this help message and exit
  --leet             Activate l33t mutagen
  --cap              Activate capitalize mutagen
  --up               Activate uppercase mutagen
  --append APPEND    Append chosen word (append 'word' to all passwords)
  --prepend PREPEND  Prepend chosen word (prepend 'word' to all passwords)
  --sort             Sort the output in ascending order based on the word length

*required arguments:
  --input INPUT      Input file name
  --output OUTPUT    Output file name
  --perm PERM        Max number of words to be combined on the same line
  --min MIN          Minimum generated password length
  --max MAX          Maximum generated password length
