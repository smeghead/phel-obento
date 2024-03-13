# phel-obento

## specification

https://github.com/o0h/iyaaaaa-na-code-example/tree/main/Obento

 * 弁当や惣菜を複数種類・複数個数、同時に注文することができる
 * 引換券(voucher)を利用すると、1番高い弁当や惣菜と交換できる(無料になる)
 * 引換券を利用できない弁当がある。惣菜には引換券を利用できない。

## Development

```bash
docker run -it --rm -v $(pwd):/usr/src -w /usr/src composer bash
# composer install
# vendor/bin/phel run src/main.phel
```

### Test

```bash
# vendor/bin/phel test
```

