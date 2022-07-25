# PlayersAndMonsters (more complex example for hierarchy)

Your task is to create the following game hierarchy: 

![image](https://user-images.githubusercontent.com/81368587/180835336-6d2006da-b40a-4676-aecc-f4caff4bca4d.png)

Create a class Hero. It should contain the following members:

•	A public constructor, which accepts:

o	username – String

o	level – int

•	The following fields:

o	username - String

o	level – int

•	Getters for username and level

•	toString() method

Hint: Override toString() of the base class in the following way:

    Sample toString()
    @Override
    public String toString() {
       return String.format("Type: %s Username: %s Level: %s",
               this.getClass().getName(),
               this.getUsername(),
               this.getLevel());
    }



  
