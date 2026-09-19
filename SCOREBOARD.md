# Scoreboard

Lower is better. `score = compressed + folder` (Dockerfile not counted). Timeout is 60s per run, 300s for the image build. Build and run have no network.

| # | name | score | compressed | code | time | status |
|---|------|------:|-----------:|-----:|-----:|--------|
| 1 | mortezam037 | 3,017,776 | 3,006,922 | 10,854 | 62.3s | ok |
| 2 | AFHINORS | 3,020,849 | 3,010,842 | 10,007 | 36.8s | ok |
| 3 | h434ni | 3,644,726 | 3,613,255 | 31,471 | 67.2s | ok |
| 4 | test | 67,109,762 | 0 | 67,109,762 | 4.0s | ok |
| — | Hornet | — | — | 0 | 0.2s | clone: fatal: could not read Username for 'https://github.com': No such device or address |
| — | Rav3n48 | — | — | 10,573 | 1.0s | compress:     exec(lzma.decompress(open('/app/s','rb').read())) |                          ^^^^^^^^^^^^^^^^^^^ | FileNotFoundError: [Errno 2] No such file or directory: '/app/s' |
