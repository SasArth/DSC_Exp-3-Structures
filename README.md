# DSC_Exp-3
##Structures
### Code:

        #include <stdio.h>
        struct student_details
        {

        char Name[50];

        int roll;

        float GPA;

        } s[5];


        int
        main ()
        {

        int i;

        printf ("Enter information of students:\n");


            // storing information
            for (i = 0; i < 2; ++i)
              {

          s[i].roll = i + 1;

          printf ("\nFor roll number%d,\n", s[i].roll);

          printf ("Enter first name: ");

          scanf ("%s", s[i].Name);

          printf ("Enter GPA: ");

          scanf ("%f", &s[i].GPA);

          }

          printf ("Displaying Information:\n\n");


              // displaying information
              for (i = 0; i < 2; ++i)
              {

          printf ("\nRoll number: %d\n", i + 1);

          printf ("First name: ");

          puts (s[i].Name);

          printf ("Marks: %.1f", s[i].GPA);

          printf ("\n");

          }

          return 0;

          }





### Output:-
![image](https://user-images.githubusercontent.com/124967782/230788015-a29508b6-069f-4043-9071-f40ba5eedba0.png)
