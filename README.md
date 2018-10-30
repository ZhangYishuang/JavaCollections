#Simple Arrays:

    int[] ints = {1, 2, 3};
    
    //sort array in order
    Array.sort(ints);
    
    //loop through array
    int[] ints = new int[10];
    for(int i = 0; i<ints.length; i++){
      ints= i * 100;
    }
    for (int value: ints){
      //print
    }

    //Copy an Array: 
    System.arraycopy(oranginalArray, beginningPosition(int), destinaitonArray, beginningPosition(int), lengthNumberOfItemWantToCopy(int));
 
#ArrayList
    List<String> list = new ArrayList<>(); 
    list.add("Beijing");
    list.add("Sydney");
    list.add("Tokyo");
    System.out.println(list);
      //Beijing Sydney Tokyo

    list.remove(0);
    System.out.println(list);
      //Sydney Tokyo  

    System.out.println(list.get(1));
      //Tokyo  
    System.out.println(list.indexOf("Tokyo"));
      //0
  
 #Hashmap: manages the unordered position
    May<String, String> map = new HashMap<>(); 
    map.put("Key", "value");
    map.get("Key")
    map.remove("key")
  
 #Looping Through ArrayList 
    Iterator<String> iterator = list.interator();
    while (iterator.hasNext()){
      String value = iterator.next();
      System.out.println(value);
    } 
      for (int value: ints){
        //loop through ints array;
    }
    
    //In Java 8
    list.forEach(System.out::println);
  
 #Looping Through HashMap 
    Set<String> keys = map.keySet();
      while (iterator.hasNext()){
      String value = iterator.next();
      System.out.println(map.get(Key));
    }
    for(String key: keys){
       //print
    }
  
