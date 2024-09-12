flake input
```
{
    inputs = {
        nixvim.url = "github:/7A1T/nixvim-config/"
    };
}
```
home-manager
```
home-manager.users.<user>.home.packages = [
    inputs.nixvim.packages.x86_64-linux.default
];
```

