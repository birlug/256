# Scoreboard

Lower is better. `score = compressed + folder` (Dockerfile not counted). Timeout is 60s per run, 300s for the image build. Build and run have no network.

| # | name | score | compressed | code | time | status |
|---|------|------:|-----------:|-----:|-----:|--------|
| 1 | mortezam037 | 3,030,172 | 3,019,458 | 10,714 | 73.4s | ok |
| 2 | h434ni | 3,644,726 | 3,613,255 | 31,471 | 66.9s | ok |
| 3 | test | 67,109,762 | 0 | 67,109,762 | 6.4s | ok |
| — | AFHINORS | — | — | 10,712 | 60.6s | compress: timeout (60s) |
| — | Hornet | — | — | 0 | 0.1s | clone: fatal: could not read Username for 'https://github.com': No such device or address |
| — | Rav3n48 | — | — | 10,575 | 1.2s | compress:     exec(__import__('lzma').decompress(open('/app/s','rb').read())) |                                        ^^^^^^^^^^^^^^^^^^^ | FileNotFoundError: [Errno 2] No such file or directory: '/app/s' |
