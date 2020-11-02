# class RoadtaxCalculator1{
public static void main(String args[]){
int vehiclePrice=350000;
String StateKeyword="AP";
switch(StateKeyword)
{
case"KA":
float roadTaxOfKA=vehiclePrice*0.10f;
System.out.println(roadTaxOfKA);
break;
case"UP":
float roadTaxOfUP=vehiclePrice*0.20f;
System.out.println(roadTaxOfUP);
break;
case"AP":
float roadTaxOfAP=vehiclePrice*0.30f;
System.out.println(roadTaxOfAP);
break;
case"TN":
float roadTaxOfTN=vehiclePrice*0.40f;
System.out.println(roadTaxOfTN);
break;
case"MH":
float roadTaxOfMH=vehiclePrice*0.50f;
System.out.println(roadTaxOfMH);
break;
case"PB":
float roadTaxOfPB=vehiclePrice*0.60f;
System.out.println(roadTaxOfPB);
break;
default:System.out.println("Choose  KA,UP,AP,TN,MH or PB");
}
}
}
