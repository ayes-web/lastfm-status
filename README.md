# lastfm-status

Simple api for showing currently scrobbling song on website

![Example iframe usage](example.png)

## Iframe usage

```html
<iframe
    src="https://lastfm.catnip.ee/status?username=YourLastfmUsername"
></iframe>
```


## Dependencies
- golang

## Running manually
```
git clone https://github.com/BatteredBunny/lastfm-status
cd lastfm-status
go run . --port 8080
```

## Running with nix
```
nix run github:BatteredBunny/lastfm-status
```
