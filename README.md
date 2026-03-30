## Trabalho Do Git - Fluxo de Versionamento

Autores: Igor Ferreira e Bianca Egea

Nota: Permitido preveamente pela professora Audrey, estamos ultilizando nosso repositório do TCC
como entrega para estre trabalho 
Para posssiveis questões futuras, Meu nome encontra-se na maioria das commits poir foram feitos em meus computadores (Tanto nos da escola quanto no peessoal)
mas duas dessas commits feitas em meu nome foram da parte da outra peça integrante do grupo: Bianca Egea 

### A seguir irá conter os seguintes conteudos:

>Diagrama de Estados do Git

>Roteiro de Comandos no Dia a Dia

>Diferença entre .zip e git clone 

>Conclusão
---
# Diagrama de Estados do GIT

### Fluxo de arquivos no GIT
```
[Working Directory]

       |

   git add
       ↓
[Staging Area]
       |
   git commit
       ↓
[Local Repository]
       |
   git push
       ↓
[Remote Repository (GitHub)]
```

---
# Roteiro de comandos

### Sequencia basica de uso
```
$ git status
$ git add >NOME DO ARQUIVO<
$ git commmit -m "MESSAGE"
$ git push origin main
```

> Mains seria o nome da branch ultilizada pelo programador
### Explicação
Estes comandos representam o fluxo basico ultilizado no dia a dia para atualização de arquivos, entregas e afins de um programados.

---

# GIT Clone e .Zip (Diferença principal)

Baixar um arquivo .zip de um repositório significa apenas obter uma cópia dos arquivos naquele momento, sem histórico de versões e sem conexão com o repositório original.

Já o comando git clone cria uma cópia completa do repositório, incluindo todo o histórico de commits e configura automaticamente a conexão com o repositório remoto, permitindo enviar (push) e receber (pull) atualizações.

###  Resumidamente

O git clone cria uma cópia completa do repositório com histórico, enquanto o .zip baixa apenas os arquivos. 

