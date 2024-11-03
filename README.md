# 🌈 SBEXT

![Static Badge](https://img.shields.io/badge/if984-SBEXT-SBEXT)
![GitHub License](https://img.shields.io/github/license/if984/SBEXT)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/if984/SBEXT)

The library was created for its own needs. I always wanted a small and simple library that would help me make the output text beautiful and convenient. There are three classes:

- **color** - sets the color of output text
- **background** - sets the background color of the output text
- **style** - sets the font style of the output text

## Usage example

```py
import sbext
from sbext import color

print(color.red + "Hello world!" + color.white)
# or red -> c01 and white -> c00
print(color.c01 + "Hello world!" + color.c00)
```

> I recommend that you open the library file in a code editor or IDE and study it so that you remember how to call the text color, background and style.
