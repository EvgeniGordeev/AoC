# adventofcode

* https://adventofcode.com
* [Collection of external solutions](credit/Bogdanp)

## 2020

https://adventofcode.com/2020

|Day|Name|Solution|Stats (`python -O -m profile 2020/01.py`)
|---|---|---|---|
|[01](https://adventofcode.com/2020/day/1)|Report Repair|[py](2020/01.py)|457 function calls in 0.065 seconds|
|[02](https://adventofcode.com/2020/day/2)|Password Philosophy|[py](2020/02.py)|17117 function calls in 0.038 seconds|
|[03](https://adventofcode.com/2020/day/3)|Toboggan Trajectory|[py](2020/03.py)|5351 function calls in 0.016 seconds|
|[04](https://adventofcode.com/2020/day/4)|Passport Processing|[py](2020/04.py)|8697 function calls in 0.020 seconds|
|[05](https://adventofcode.com/2020/day/5)|Binary Boarding|[py](2020/05.py)|4323 function calls in 0.012 seconds|
|[06](https://adventofcode.com/2020/day/6)|Custom Customs|[py](2020/06.py)||
|[07](https://adventofcode.com/2020/day/7)|Handy Haversacks|[py](2020/07.py)||


## tools

download input of last day:

* install:

```bash
go get -u github.com/GreenLightning/advent-of-code-downloader/aocdl
go build -v github.com/GreenLightning/advent-of-code-downloader/aocdl
mv aocdl /usr/local/bin/
echo '{"session-cookie": "xxx"}' > $HOME/.aocdlconfig
echo "
#!/usr/bin/env bash
aocdl --force
pbcopy <input.txt
" > get.sh
chmod +x get.sh
```

* download to input.txt and copy to clipboard:

```bash
./get.sh
```