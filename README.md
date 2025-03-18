# PIPE-CLI

## INSTALL

```bash
curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"
```
```bash
chmod +x pop
```
# MAKE Directory

```bash
mkdir download_cache
```

# SIGN UP WITH 

```bash
./pop --signup-by-referral-route 1fa7623cc0cd7a9d
```

# START NODE WITH

1.
```bash
sudo ./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <KEY> --enable-80-443
```

2.GET NODE ID AND TOKEN THIS 

```bash
nano ~/node_info.json
```

A. copy that file data and must save it

b.Ctrl+x to Exit 

3.TO CHECK NODE STATUS

```bash
./pop --status
```

4.TO CHECK POINTS

```bash
./pop --points
```

5.TO GET REFERRAL KEY

```bash
./pop --gen-referral-route
```

# OTHER INFO

1. Docs- https://docs.pipe.network/devnet-2
2. Check Points & Status From Dashboard -: https://dashboard.pipenetwork.com/node-lookup
3. must maintain a historical score above 80% for at least 7 days

