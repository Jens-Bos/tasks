# Tasks
python3 argparse to do list

## Database

`tasks` uses `~/tasks.txt` to store entries. If this file can't be found, `tasks` offers to create it.

## Usage

Output for `tasks -h`:

```
usage: tasks [-h] {list,add,finish} ...

simple to do list

optional arguments:
  -h, --help         show this help message and exit

Commands:
  supported commands

  {list,add,finish}
    list             shows all list items
    add              adds item to list
    finish           removes item from list
```

### list

Output for `tasks list -h`:

```
usage: tasks list [-h]

optional arguments:
  -h, --help  show this help message and exit
```

usage: `tasks list`

### add

Output for `tasks add -h`:

```
usage: tasks add [-h] [text [text ...]]

positional arguments:
  text        add an item

optional arguments:
  -h, --help  show this help message and exit
```

example: `tasks add hello world`

### finish

Output for `tasks finish -h`:

```
usage: tasks finish [-h] [{} [{} ...]]

positional arguments:
  {}          remove an item

optional arguments:
  -h, --help  show this help message and exit
```

example: `tasks finish 1`
