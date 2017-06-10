class gamezork
{
  public static void main (String[] args)
  {
    String input;
    String []items= new String [6];
    items[0]= "Sword and armor";
    items[1]= "Long Sword and metal armor";
    items[2]= "Magic Sword and crystal armor";
    items[3]="Dark Sword and evil armor";
    items[4]= "Holy Sword and god armor";
    items[5]= "Ben's Sword and Ben's Armor";
    
    int []Dmg=new int[4];
    Dmg[0]=10;
    Dmg[1]=15;
    Dmg[2]=20;
    Dmg[3]=30;
    
    int []Hp=new int[4];
    Hp[0]=100;
    Hp[1]=170;
    Hp[2]=300;
    Hp[3]=500;
    
    
    int []ItemDmg= new int [6];
    ItemDmg[0]=5;
    ItemDmg[1]=7;
    ItemDmg[2]=10;
    ItemDmg[3]=20;
    ItemDmg[4]=50;
    ItemDmg[5]=100;
    
    int []ItemDef= new int [6];
    ItemDef[0]=3;
    ItemDef[1]=5;
    ItemDef[2]=10;
    ItemDef[3]=20;
    ItemDef[4]=40;
    ItemDef[5]=80;
    
    String[] Monsters=new String [4];
    Monsters[0]="Doggy";
    Monsters[1]="Flash wolf";
    Monsters[2]="Dark solider";
    Monsters[3]="Boss Mr.Linseman";
    
    int [] MonstersHp= new int [4];
    MonstersHp[0]=50;
    MonstersHp[1]=100;
    MonstersHp[2]=300;
    MonstersHp[3]=1000;
    
    int [] MonstersDmg= new int [4];
    MonstersDmg[0]=10;
    MonstersDmg[1]=30;
    MonstersDmg[2]=70;
    MonstersDmg[3]=100;
    
    System.out.println("Welcome to the game of zork. You will choose one out of the three doors. Monsters might hiden behind the door. Try to get out of the maze.");
    System.out.println("Type number 1-3 for the door number");
    System.out.println("PLayer damage: "+ Dmg[0]+ " Health: "+ Hp[0]+" Defence: "+ItemDef[0]);
    /*  
     String []skills= new String [4];
     skills[0]= "fire ball";
     skills[1]= "ice storm";
     skills[2]= "one shot";
     skills[3]= "bloody pool";
     skills[4]= "reborn";
     
     
     
     int [] SkillsDmg= new int [4]
     SkillsDmg[0]= ;
     SkillsDmg[1]= ;
     SkillsDmg[2]= ;
     SkillsDmg[3]= ;
     SkillsDmg[4]= ;
     */
    input = In.getString();
    
    if (input.equals("1"))
    {
      
      firstDoor(Dmg,Hp,items,ItemDmg,MonstersDmg,ItemDef,MonstersHp,Monsters);
    }
    else if (input.equals("2"))
  {
    secondDoor(Dmg,Hp,items,ItemDmg,MonstersDmg,ItemDef,MonstersHp,Monsters);
  }
    
  }
  
  
  public static void firstDoor(int[] Dmg,int[]Hp,  String[] items, int[] ItemDmg, int[] MonstersDmg,int[]ItemDef, int[] MonstersHp, String[] Monsters  ) {//2 door
    {
      
      
      
      int Lv2DmgItem0;
      
      
      boolean monsterAlive = true;
      System.out.println("First Door");
      System.out.println("There is a monster !!!!");
      System.out.println("Lv 1 Monster Doggy");
      
      
      
      
      do{
        if (MonstersHp[0]<=0)
        {
          monsterAlive = false;
        }else{
          Hp[0]=Hp[0]-MonstersDmg[0];
          MonstersHp[0]= MonstersHp[0]-Dmg[0];
          System.out.println(Monsters[0]+" damage "+MonstersDmg[0]);
          System.out.println("Doesn't Hurt!");
          System.out.println("Your Damage "+ Dmg[0]);
          System.out.println("Your health: "+Hp[0]);
          System.out.println(Monsters[0]+" HP "+ MonstersHp[0]);
        }
      } while (monsterAlive);
      
      
      
      
      System.out.println("You win the battle!!!!");
      System.out.println("Basic Hp + 20, Basic Dmg + 5");
      
      System.out.println("You get "+items[0]);
      Lv2DmgItem0=Dmg[1]+ItemDmg[0];
      
      System.out.println("Your current Hp: "+ Hp[0] + " Your damage: "+ Lv2DmgItem0 + " Your defence: "+ItemDef[0]);
    }
  }
  
  
  
  
  public static void secondDoor(int[]Dmg,int[]Hp,String[]items,int[]ItemDmg,int[]MonstersDmg,int[]ItemDef,int[]MonstersHp,String[]Monsters)
  {
    
    System.out.println("Second Door");
  System.out.println("Your receive an item !!!!");
  System.out.println("Item "+ items[0]+" received");
  System.out.println("Your damage + "+ ItemDmg[0]+" Your defence + "+ ItemDef[0]);
                     
                     
                     }
}

    
    
      
      
      
      
