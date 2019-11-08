# Wordcount Example

## Objectives of this labs
- Count the frequency of words in files

## Environment
- [Java]()
- [Maven](https://www.mkyong.com/maven/how-to-install-maven-in-windows/)

## Run Local

- Please, remove folder `output` inside project root folder if existed

```
mvn install exec:java -Dexec.mainClass="vn.fpt.App" -Dexec.args="./input ./output"
```

## Run on Hadoop

### Build jar package

```
mvn package
```

### Copy jar in to a node in hadoop cluster

```
scp target/x.jar user1@118.68.170.134:~/
```

### Submit job on cluster

```
hadoop -jar ...
```