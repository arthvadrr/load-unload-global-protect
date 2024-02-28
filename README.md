# load-unload-global-protect

An NPM module for launching/quitting GlobalProtect since they make it such a pain to do so. (uses shell)

## Usage
Install this module from github:
```npm install -g git+https://github.com/arthvadrr/load-unload-global-protect.git```

Be sure to give permissions to the shell scripts (only if needed, try running the script first)
```chmod +x start.sh stop.sh```

Symlink it (if not using npm)

```npm link```

To start:
```gprotect```

To stop:
```gprotectstop```
