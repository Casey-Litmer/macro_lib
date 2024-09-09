```commandline
pip install macro_lib
```

### Macros for type conversions, recursive search, file handling, etc...

-----------
### typemacros

```commandline
import macrolib.typemacros
```
Includes:
- standardization of unions, intersections, and compliments for all base iterables
- recursive find and replace for all nested data structures
- automatic function argument reduction (reductive polymorphism)

-----------

### filemacros

```commandline
import macrolib.filemacros
```
Includes:
- `get_script_dir` function to return the directory of the call location
  
 (this is different from `os.getcwd` as it will retun the location of the file
  making the function call)
 - `full_walk` returning full paths from `os.walk`

-----------

### jsonmacros

```commandline
import macrolib.jsonmacros
```
Includes:
- json saving and loading with default format option
