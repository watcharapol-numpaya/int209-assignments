# Linux assignment

## 1. Excercise File
```bash
mkdir -p wipcamp12/{programmer,website,network,ux-ui}  
touch wipcamp12/slide01.txt
cd wipcamp12
for slide in slide02.txt slide03.txt ; do cp -r  slide01.txt "$slide" ; done
cp -r ../wipcamp12/ ../wipcamp13/
rm ../wipcamp13/slide03.txt
mv slide01.txt ../wipcamp13/newslide.txt
rm -r ../wipcamp12 ../wipcamp13
```