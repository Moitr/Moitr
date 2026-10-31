### Hi there 👋

```nix
{
  description = "A student shaping code and chasing poetry. I build with logic, live with curiosity, and find beauty between the lines. Still learning, still creating, still becoming.";
  inputs = { };
  outputs = inputs: {
    about = {
      nickname = "Moitr";
      pronouns = "他·He·Il";
      languages = with pkgs.lang; [ ch en];
    };
  };
}
```
