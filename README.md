# json_serialize_project
## Steps to generate json serialize g file
1. Add bean/model file to generate into the lib folder
2. Run "flutter pub run build_runner build" in terminal
3. Change the g dart file to null safety by replacing the
```
json['id'] as String 
```
TO
```
Util.parseStr(json['title'])
```
