# Números Primos en JAVA.

## Bucle FOR.
```java
public class NumerosPrimos {

	public static void main(String[] args) {	
		  boolean esPrimo;
		  int minimo=1, maximo = 100;
		  
		  for(int i = minimo;i <= maximo;i++){		 
		      
			  esPrimo=true;
		       
		      for(int j=2;j<i;j++){
		    	   if(i%j == 0){
		    		   esPrimo = false;
		    	   }
		       }
		       if(esPrimo){
		    	   System.out.println(i);
		       }
		  }
	}
}
```
## Bucle WHILE.
