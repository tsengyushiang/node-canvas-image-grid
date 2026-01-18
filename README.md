# Node-canvas

## Quick start

### Setup

```
npm install
```

### Commands

```
PS C:\Users\node-canvas-image-grid> node index.js -h
Usage: index [options]

Options:
  -i, --inputs [strings...]     input filenames
  -o, --output <string>         output filename
  -r, --resolution [number...]  output resolution [width,height]
  -p, --padding [number...]     padding [x,y]
  -h, --help                    display help for command
```

### Example

-  Git Bash + Docker
```
docker run --rm -v "/$(pwd):/app" -w //app node:20 node index.js -i 1.jpg 2.jpg 4.jpg 3.jpg -o ./output.png -r 1200 1800 -p 80 1
```
