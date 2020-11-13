# ops-ip

Get IP addresses of a machine.

## Usage

Run `ops-ip` command without arguments to get all IP addresses of a local machine.

Running `ops-ip` with `--help` option will show you a short usage message.

```
Get IP addresses of a machine

Usage: ./ops-ip [options]

Options:
  -4, --ipv4        Get IPv4 only
  -6, --ipv6        Get IPv6 only
  -p, --private     Get private IPs only
  -u, --public      Get public IPs only
  -l, --link-local  Get link-local IPs only
  -o, --loopback    Get loopback IPs only
  -f, --filter      Filter IPs list by pattern
  -c, --count       Count of IPs in list
  -d, --delimiter   Custom output delimiter
  -h, --help        Print help and exit
```

## Installation

Use any method appropriate for you to get [ops-ip](ops-ip) file on your system.

For example, git clone and create symlink in the current user's bin directory:

```
$ git clone https://github.com/ops-tools/ops-ip.git
$ mkdir -p ~/bin/ && ln -s $(pwd)/ops-ip/ops-ip ~/bin/
```

Or to install it globally, create another symlink in the system-wide bin directory:

```
$ sudo ln -s $(pwd)/ops-ip/ops-ip /usr/local/bin/
```

## Development

Please follow [Shell Style Guide](https://google.github.io/styleguide/shell.xml) by Google when writing new code or making changes.

## License

This software is distributed under the [MIT license](https://github.com/ops-tools/ops-docker/blob/master/LICENSE).
