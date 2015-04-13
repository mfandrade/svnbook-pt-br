## Quando adicionar um novo termo nesta lista? ##

Quando você encontrar-se pensando "este termo fica melhor deste jeito ou daquele?".  Termos cuja tradução não é óbvia ou trivial tendem a ser traduzidos de diferentes formas por diferentes tradutores.  Nesse caso, apresente o termo à equipe (através da lista de discussão) para discutir qual a melhor tradução para o termo, verificando antes se o termo encontra-se no [arquivo de tradução do svn](http://svn.collab.net/repos/svn/trunk/subversion/po/pt_BR.po) ou no [do TortoiseSVN](http://tortoisesvn.tigris.org/svn/tortoisesvn/trunk/Languages/Tortoise_pt_BR.po).

Na primeira ocorrência de cada termo traduzido, deverá ser incluído o termo original indicando o nome do termo em inglês entre parênteses e envolvido no elemento <[foreignphrase](http://www.docbook.org/tdg/en/html/foreignphrase.html)>. Por exemplo:

Frase original:

```
<para>
  For this reason, Subversion 1.2 and later offers a feature known as locking, often known as...
</para>
```

Frase traduzida:

```
<para>
  Por essa razão, o Subversion 1.2 e versões superiores oferecem um recurso conhecido como travamento
  (<foreignphrase>locking</foreignphrase>), muitas vezes conhecido como...
</para>
```

Eis a lista, em ordem alfabética.

| Apache HTTP Server                    | Servidor Apache HTTP Server |
|:--------------------------------------|:----------------------------|
| Blanket access                        | Acesso geral |
| Branch                                | Ramificar (v); Ramo (s) |
| Checkout                              | Obter cópia |
| Command-line                          | Linha de comando |
| Command-line client program           | Programa cliente de linha de comando |
| Commit                                | Submeter (v); Submissão (s) |
| Daemon process                        | Processo daemon |
| Externals definition                  | Definição externa |
| Feature                               | Recurso |
| Language binding                      | Ligação de linguagem |
| Lock                                  | Travar (v); Trava (s) |
| Merge                                 | Fundir (v); Fusão (s) |
| Plug-in module                        | Módulo plug-in |
| Repository dump                       | Dump de repositório |
| Repository dump stream                | Fluxo de dump de repositório |
| Standalone server program             | Programa servidor independente |
| Subversion repository                 | Repositório Subversion |
| Tag                                   | Rótular (v); Rótulo (s) |
| Third-party tools                     | Ferramentas de terceiros |
| Versioned file                        | Arquivo sob controle de versão |
| Working copy                          | Cópia de trabalho |
| Switch                                | Comutar (v); Comutação (s) |
| Siwitching                            | Comutação |

(v) verbo; (s) substantivo