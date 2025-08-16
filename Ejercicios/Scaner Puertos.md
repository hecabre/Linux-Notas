```
#!/bin/bash
function ctrol_c(){
        echo -e "\n\n[!] Saliendo"
        exit 1
}

trap ctrol_c INT

for port in $(seq 31000 32000); do
        (echo '' > /dev/tcp/localhost/$port) 2>/dev/null && echo "[+] Puerto abierto -> $port"&
done; wait

```