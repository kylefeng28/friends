# friends

See who's online on your \*NIX server! Perfect for campus servers.

## Installation
- Place the `friends` script somewhere in your PATH.
- Export the `MYFRIENDS` variable in your `.bashrc` or `.tcshrc` file
  - Format is usernames separated by a pipe (|)
  - Example: `export MYFRIENDS="alice|bob|charlie"

## Commands
### List friends

```
friends list
```

Sample output:

```
1 friend is online!
alice
```

```
3 friends are online!
alice bob charlie
```

```
No friends are online :(
```

### Show friend info

```
friends info
```

Sample output:

```
alice:
On since Wed Feb 8 00:34
Idle for 1:29m
```
