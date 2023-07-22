# Decrement-and-Increment-in-c-programming


      #include <stdio.h>
      void increment();
      void decrement();
      int i;
      main()
      {
	    printf("\n i=%d",i);
	    increment();
	    increment();
	    decrement();
	    decrement();
      }
      void increment()
      {
	    i=i+1;
	    printf("\n On incrementing i=%d",i);
	    i=i+1;
      }
      void decrement()
      {
	    i=i-2;
	    printf("\n On decrementing i=%d",i);
	    i=i-1;
      }
