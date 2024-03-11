# RoslynInvalidUtf8
Shows an invalid UTF-8 source code file that compiles ok but fails at runtime because it converts invalid UTF-8 sequences to the � character, resulting in two identical string keys.
