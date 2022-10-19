# Reason Proto

## add
```shell
# normal add
git submodule add -b master --name api/greeter-proto https://github.com/go-cinch/greeter-proto.git ./api/greeter-proto

# or force add
git submodule add -f -b master --name api/greeter-proto https://github.com/go-cinch/greeter-proto.git ./api/greeter-proto
```

## update
```shell
git submodule update --force --recursive --init --remote
```
