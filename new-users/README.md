# Wordcount Example

## Objectives of this labs
- Count the frequency of words in files

## Environment
- [Java]()
- [Maven](https://www.mkyong.com/maven/how-to-install-maven-in-windows/)

## Run

- Please, remove folder `output` inside project root folder if existed

```
mvn install exec:java -Dexec.mainClass="vn.fpt.App" -Dexec.args="./input ./output"
```