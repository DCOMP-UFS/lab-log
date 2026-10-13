# lab-log
Registro de logs de configuração de serviços de redes

## Registro de histórico de comandos na AWS

modifique a forma como a AWS formata seu histórico de comandos:

Após criar uma nova EC2,  execute o comando(na mesma linha):

```
echo 'export HISTTIMEFORMAT="%Y-%m-%d %H:%M:%S "' >> ~/.bashrc
```

Depois, para valer a alteração execute o comando: 

```
source ~/.bashrc
```


