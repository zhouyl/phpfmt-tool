# PHPFMT-tool

## Installation

### Via Composer

```bash
composer require zhouyl/phpfmt-tool
```

### Configuration file lookup order

1. $PWD/.phpfmt.ini (customize)
2. $HOME/.phpfmt/.phpfmt.ini (global)

### Customize the configuration file

```bash
cp vendor/zhouyl/phpfmt-tool/.phpfmt.ini .
```

### Customize the default formatting directories (e.g. laravel 5.x)

```bash
echo "./app ./bootstrap ./database" > ./.fmtdirs
```

### Usage

```bash
cd /workspace/myapplication
vendor/bin/phpfmt .
```

## Global Installation

```bash
wget --no-check-certificate https://github.com/zhouyl/phpfmt-tool/raw/master/phpfmt -O /usr/local/bin/phpfmt
chmod +x /usr/local/bin/phpfmt
cd /workspace/myaplication
phpfmt .
```

## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
