# translator

### I watched a youtube video this morning that peaked my interest with the python translator model, as such i made a really simple application in python...

![image](https://user-images.githubusercontent.com/56073739/129480729-7bdc3397-f45f-46f8-94cf-952cd729580d.png)

```
# Import the module
from translate import Translator

# Literally just this method to translate any phrase to Spanish
def translate_to_spanish(phrase):
    translator = Translator(to_lang="es")
    return translator.translate(phrase)

# Translate anything you want...
if __name__ == "__main__":
    print(translate_to_spanish("This is a test phrase for the Joeman empire"))

>>  Esta es una frase de prueba para el imperio Joeman
```

### It waa then i thought, oooh it would be fun to make a django web application out of it wouldn't it! (well yes but it's so heavyweight for the kind of application that this is). So the next logical step was Vue and npm.

# I feel like this has helped alot with my comprehension with vue, so i hope you enjoy this repo and as always have fun with it :shipit:
