* IpTables: Trabalha com protocolo de IP, nas camadas de transporte e redes;
* Squid: Trabalha na camada de aplicação;

#### -A
* Adiciona no fim

#### -I
* Adiciona no início

#### -D
* Apaga regra digitada

#### -L
* Listas as regras

#### -P
* Define padrão de cadeias
* Comando "iptables -P FORWARD DROP" - Roteamento
* Comando "iptables -P INPUT DROP" - Bloqueia a entrada(Esgotado o tempo de limite do pedido)

#### -F
* Apaga todas as regras

#### -s
* Origem

#### -d
* Destino

#### -p
* Protocolo

#### --dport
* Porta de destino

#### --sport
* Porta de origem

#### -j
* Ação (DROP - ACCEPT -REJECT)

#### -t
* Tipo de tratamento (Cadeias: Nat, Filter, Mangle)
* OBS: Sempre que digitar um comando, tem que passar a cadeia na primeira configuração

#### INPUT
* Entrada

#### OUTPUT
* Saída

#### FORWARD
* Roteamento
