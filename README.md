# sshamble

SSHamble is research tool for SSH implementations that includes:

* Interesting attacks against authentication
* Post-session authentication attacks
* Pre-authentication state transitions
* Authentication timing analysis
* Post-session enumeration

This project is a work-in-progress and likely to change quickly.

You can reach our team via research[α𝓽]runZero.com.

https://SSHamble.com/

## Usage

```
$ go run main.go -h

▀██▄  ▀███████████████████████████████████████████████████████████████████████████████████████████
  ▀██▄
    ▀██▄     ▄████████  ▄████████  ██     ██  ▄███████▄  ▄████████▄  ████████▄  ██        ▄███████
      ▀██▄   ██         ██         ██     ██  ██     ██  ██  ██  ██  ██     ██  ██        ██
        ███  ▀███████▄  ▀███████▄  █████████  █████████  ██  ██  ██  █████████  ██        ████████
      ▄██▀          ██         ██  ██     ██  ██     ██  ██  ██  ██  ██     ██  ██        ██
    ▄██▀     ████████▀  ████████▀  ██     ██  ██     ██  ██  ██  ██  ████████▀   ▀██████  ▀███████
  ▄██▀
▄██▀  ▄███████████████████████████████████████████████████████████████████████████████████████████

An exploration tool for (in)secure shell services.


Start a network scan using:

$ sshamble scan -o results.json 192.168.0.0/24

Analyze the results using:

$ sshamble analyze -o results-directory results.json

Usage:
  sshamble [command]

Available Commands:
  analyze     Analyzes a scan JSON output file and buckets results
  help        Help about any command
  scan        Enumerates a set of targets for SSH capabilities and exposures

Flags:
  -h, --help   help for sshamble

Use "sshamble [command] --help" for more information about a command.
```