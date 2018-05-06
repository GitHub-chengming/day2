# day2
小计
public static void main(String[] args){
  int wuwei=31234;
  System.out.println("五位数时:"+wuwei);
  int qianwei=wuweishu/10000;
  System.out.println("第五位数是:"+qianwei);
  int baiwei=wuwei/1000%10;
  System.out.println("第四位数是:"+baiwei);
  int shiwei=wuwei/100%10;
  System.out.println("第三位数是:"+shuwei);
  int gewei=wuwei/10%10;
  System.out.println("第二位数是:"+gewei);
  int zuihou=wuwei/%10;
  System.out.println("第一位数:"+zuihou);
  int zongshu=qianwei+baiwei+shiwei+gewei+zuihou;
  System.out.println("五位数之和:")+zongshu;
}
