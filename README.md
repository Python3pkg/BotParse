BotParse
========

A modified version of argparse to make bot making easer

`BotParse(description=None, epilog=None, add_help=True)`

To use `BotParse` create an instance of the `BotParse` class

Then you simply add commands. Commands can then be used like normal argparse parsers

```python
from botparse import BotParse

parser = BotParse(
    "This is the description",
    "This is the epilog",
)

command = parser.add_command(
    '!list', help="This is list's help mesage"
)
```
