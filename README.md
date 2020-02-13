# cleric-class
//クレリック　クラス
public class Cleric {
    
   //クレリック生成
   String name;
  
   int hp = 50; int hp;
   int mp;
   final int saidai hp = 50;
   int mp = 10;
   final int saidai mp = 10;
   
  }
  public void selfAid(){
      this.mp - =5;
      System.out.println(this.name + "はセルフエイドを唱えた");
      this.hp = saidai hp;
      System.out.println(this.name + "はHPが最大まで回復した");
    
       System.out.println(this.name +"は"+ sec+ "秒祈った");
       //ランダム乱数　回復
       int kaihuku = new java.util.Random().nextInt(3);
       
       
       //祈り回復量
       int goukeikaihuku =sec*kaihuku ;
       
       System.out.println("MPが"+goukeikaihuku + "回復した");
       
       return goukei kaihuku;
  }
  }
  
