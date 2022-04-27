# ilab-exercicio-semana1

Primeiramente a VPC foi criada. Segui para a criação de 3 subnets, cada uma em um datacenter diferente. Para saber qual IP usar na criação das subnets, utilizei a calculadora de IP online.
Segui para a criação do Internet Gateway e a anexação (attach) dele à VPC.
O Internet Gateway foi incluído na Route Table, com Destination para todos (0.0.0.0/0).
Adicionei explicitamente as subnets à Route Table.
Foi criada instância EC2 na VPC criada, com Auto-Assign Public IP Enable para permitir acesso externo.
A máquina criada foi acessada por SSH via terminal.
