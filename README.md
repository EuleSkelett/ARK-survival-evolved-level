#include <stdio.h>
int main ()
{
  int x=3, k=0, l=1;
  int i = 0;
  while ( i<1500)
  {
  	if(i!=x){
  		printf("ExperiencePointsForLevel[%d]=%d,",i, k);
  		k+=l;
	  }
	else{
		l+=1;
		x=x+3;
		printf("ExperiencePointsForLevel[%d]=%d,",i, k);
		
	}
	

  	i++;
  }
  return 0;
}
