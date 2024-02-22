### Abrindo dois arquivos ao mesmo tempo dividido horizontalmente
```bash
vim -o file1.txt file2.txt
```
Quando abrir se precisar trocar de documento, basta fazer CTRL + wwi

### Abrindo dois arquivos ao mesmo tempo dividido verticalmente
```bash
vim -O file1.txt file2.txt
```

Para sair do documento navegue até o documento com CTRL + ww e entre no modo de
comando com ESC e digite `:q`.

Para sair de todos os documentos abertos use `:qa`i


## Comando split e vsplit

Ao abrir um arquivo ex.: `vim text.txt`, quando o arquivo estiver aberto você pode abrir outro 
arquivo dividindo da tela verticalmente ou horizontalmente com o comando `split` e `vsplit`.

Digite `:split ` e dê um TAB, isso vai autocompletar com os nomes dos arquivos do mesmo diretório,
selecione o arquivo e dê ENTER, o segundo arquivo será aberto horizontalmente, o mesmo ocorre com
o comando `:vsplit `, a diferença é que ele vai abrir o arquivo verticalmente.
