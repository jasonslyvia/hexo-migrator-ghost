# hexo-migrator-ghost

Ghost migrator for Hexo.

## Install

``` bash
$ npm install hexo-migrator-ghost --save
```

## Usage

### Export from Ghost

Visit `http://yourblog.com/ghost/debug/` , click `Export` and download the JSON file.

### Import to Hexo

Execute the following command after installed. `source` is the file path exported by Ghost.

``` bash
$ hexo migrate ghost <source>
```

[Hexo]: http://zespia.tw/hexo
