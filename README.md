## Use on fresh install
To use this flake to setup a new system, follow these instructions:

1. Boot into live USB
2. nix-env -iA nixos.git
3. git clone <repo url> /mnt/.setup
4. nixos-install --flake .#rober
5. reboot
6. sudo rm -r /etc/nixos/configuration.nix
