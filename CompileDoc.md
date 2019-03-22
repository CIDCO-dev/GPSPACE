## Compile

 - To compile gpspace.f you will need to download and extract both folders in the [Release](https://github.com/HugoValcourt/GPSPACE/releases/tag/v1.10-beta) tab. When done, extract them both in the repo's root. For 'external_sources', you will need to rename and move both folders to the repo's root (rename to anything, it is just to not overwrite the folders already in place with the same name).
 - Then you have to run this command at the root of the folder: ('executable' being the name of your executable output file. e.g. gpspace)
```
gfortran -finit-local-zero -O2 -o 'executable' gpspace.f */*.F
```

