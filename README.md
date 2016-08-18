#[NixOS](http://nixos.org) Black [SLiM](http://slim.berlios.de/) Theme
![preview](https://github.com/edwtjo/nixos-black-theme/raw/master/preview.png)

To use this theme in NixOS set your SLiM configuration settings like so:

```

  services.xserver.displayManager.slim = {
    enable = true;
    theme = pkgs.fetchurl {
      url = "https://github.com/edwtjo/nixos-black-theme/archive/v1.0.tar.gz";
      sha256 = "13bm7k3p6k7yq47nba08bn48cfv536k4ipnwwp1q1l2ydlp85r9d";
    };
  };

```
