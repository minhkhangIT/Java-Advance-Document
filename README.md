# Java Advance Document
Learn advance java

### Exception
![img](https://user-images.githubusercontent.com/99189713/164143960-a731dd7d-fc69-4dc4-a25f-4ecd6178bb53.png)

- IOException is an exception which programmers use in the code to throw a failure in Input & Output operations. 
- SQLException is an exception that provides information on a database access error or other errors.
- ClassNotFoundException is a checked exception in Java that occurs when the JVM tries to load a particular class but does not find it in the classpath.
- RuntimeException is the superclass of those exceptions that can be thrown during the normal operation of the Java Virtual Machine.

 ```java
 try{
      int data=100/0;
 }catch(Exception a){
        System.out.println(a);
        System.out.println("rest of the code...");
  }
```
### Wild Card

 ```java
 public static void main(String[] args) {
        List <Integer> arrayLists = new ArrayList<>();
        arrayLists.add(5);
        arrayLists.add(6);
        arrayLists.add(8);
        xuatList(arrayLists);
        List <String> arrayLists2 = new ArrayList<>();
        arrayLists2.add("ccc");
        arrayLists2.add("cccsdf");
        arrayLists2.add("ccsdfc");
        xuatList(arrayLists2);

    }
    public static void xuatList(List<?> list){
        System.out.println(list);
    }
```
