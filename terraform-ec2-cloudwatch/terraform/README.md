# terraform ec2 cloudwatch

## Pré requisitos

* terraform
* aws cli configurada

## Como usar?

1. Ajuste variables.tf de acordo com o seu ambiente

2. Para criar o ambiente:

```bash
make start
```

*Pode levar até 5min para a instância se tornar operacional*

3. Acesse a instância e execute:

```bash
sudo su - 
bash -c 'cd /opt/bancodigital && git checkout monitoria-e-tracing-tc3-tl1 && make start'
```

4. Para destruir o ambiente:

```bash
make stop
```



