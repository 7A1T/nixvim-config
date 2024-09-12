flake input
```
{
    inputs = {
        nixvim.url = "github:dc-tec/nixvim"
    };
}
```
home-manager
```
home-manager.users.<user>.home.packages = [
    inputs.nixvim.packages.x86_64-linux.default
];```
`
