# dart-list-loop-concept
dart-list/loop concept
void main() {
  
  
  var bname=[1,3,4,"marry"]; // inferred list      ist method
  
  List <String>name=["firstname","lastname","middelename"]; //statically typed list      2nd method
  
  name.add("fourth"); // how to add string in list 
  name.add("five"); // how to add string in list 
  name[1]=("2nd namee");// how to exchange name
  name[3]=(" ");//how to remove string
  

  
  List info=[]; //declarition variable    third method of list
  info.add(1);//intialization variable      add integer in list
  info.add(2);//add integer in list
    info.add("maryam");//add STR in list
  info.add("iiui");//add STR in list
  info.add("uiux");//add STR in list
  
  
  
  print("i am first : $bname");//print inferred list
  
  
  print("i am 2nd :  $name");//print statically typed list
  
  
   print("i am third  : $info");//print inferred list
  
  
    for(var item in bname)//use for loop for inferred variable
    
  
  {
  
  print("i am fourth :  $item");}
  
  
  
     for(String item in name)//use for loop for inferred variable
    
  
  {
  
  print("i am five:  $item");}
  
    for(var item in info)//use for loop for inferred variable
    
  
  {
  
  print("i am six:  $info");}
  
  
  

  }  //voidddddddddddddddddddddddd   end    
  
