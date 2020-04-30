# Roastmap

The purpose of the utility is preheating up Nginx cache through sitemap.xml. 
It's reduces wait of robots for getting contents page. 

## Docker usage

```bash
docker run -it --rm --init -e DEBUG=1 spacetabio/roastmap:1.0.0 \
    start https://google.com --parallel=3 --times=1 --delay=3000
```

## Usage

```bash
bin/roastmap start https://google.com --parallel=3 --times=1 --delay=3000
```

## License

The MIT License

Copyright © 2020 spacetab.io, Inc. https://spacetab.io

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
