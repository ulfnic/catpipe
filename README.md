# catpipe

Create a named pipe and cat it's contents perpetually.

## Installation
```bash
cd /usr/local/bin
sudo wget https://github.com/ulfnic/catpipe/blob/main/catpipe
sudo chmod +x catpipe
```

## Syntax
```bash
catpipe
  -d|--pipe-dir    # Optional, (default: /tmp) specify the directory to use for named pipes
  -c|--clip        # Optional, place the path to the named pipe in the clipboard using clip-in
```

## License
Licensed under Zero-Clause BSD (0BSD). See LICENSE for details.
