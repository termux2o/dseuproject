#include <stdio.h>
 #include<stdlib.h>// for system() function
 int book()
{
    int o;
    printf("enter 1:for pic\n2 for coa\n 3 for se\n 4 for it\n 5 for maths\n 6 for sel \n 7 for english:");
    scanf("%d",&o);
printf ("\n=======================================================================================\n");
if(o==1)
{
printf ("\t\t\t\t\t\t\t\t\t\tPIC:Books\n1. Programming in ANSI C, E.Balagurusamy\n2. Computer Basics and C Programming, V. Rajaraman\n3. The Artof Programming Through Flowcharts & Algorithms, Anil Bikas Chaudhuri.\nb) Open source software and website address: \n1. Code::Blocks: https://www codeblocks.org/\n2. Visual Studio Code: https://code.visualstudio.com/\n");
}
else if(o==2)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\t\t\tCOA:Books:\n1. Morris Mano, Computer System Architecture, 3rd Edition, Prentice-Hall of India Private Limited, 1999.\n2. WIliam Stallings, Computer Organization and Architecture, 4th Edition, Prentice Hall of India Private Limited, 2001 \n3. Subrata Ghosal,” Computer Architecture and Organization” , Pearson 2011\n4. Malvino, “Digital Computer Electronics: An Introduction to Microcomputers”, McGraw Hill\nb) Open source software and website address: 1. Electronics Workbench\n2. MultiSim\n");}
else if(o==3)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\t\t\tSE books:\n1. K. K. Aggarwal & Yogesh Singh, “Software Engineering”, 2nd Ed., New Age International, 2005.\n2. Rajib Mall, “Fundamental of Software Engineering”, 3rd Edition, PHI Learning Private Limited\n3. I. Sommerville, “Software Engineering”, 9th Edition Pearson Edu.\n4. Jalote Pankaj , “Software Engineering”, Narosa Publication\n5. R. S. Pressman, “Software Engineering  A practitioner's approach”, 5th Ed., McGraw Hill Int. Ed., 2001.\n6. James Peter, W. Pedrycz, “Software Engineering: An Engineering Approach”, JohnWiley&Sons.\n ");
}
else if(o==4)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\t\t\tIT books:\n1. Alex Leon and Mathews Leon, “Fundamentals of Information Technology”, Leon Techworld, 2007.\n2. P. KSinha and Priti Sinha , “Computer Fundamentals”, BPB Publications, 2007.\n 3. Malvino and Leach, “Digital Principles and Application”, TMH, 1999.\n4. Alex Leon and Mathews Leon, “Introduction to Computers”, Vikas Publishing House, 2007.\n5. Norton Peter, “Introduction to computers”, TMH, 4th Ed., 2006.\n6. Simon Haykins, “Communication System”, John Wiley & Sons, 2006.\n7. B. Basaraj, “Digital Fundamentals”, Vikas Publications, 1999.\n8. V. Rajaraman, “Introduction to Information Technology”, PHI, 2006.");
}
else if(o==5)
{
printf("\n****************************************************************************************************************************\n");
printf ("Maths:1. Kreyszig E., Advanced Engineering Mathematics, John Wiley, New York, 1999\n2. Gerald, C.F., Wheatley P.O., Applied Numerical Analysis, Pearson, 2007.\n3. Grewal B.S., Higher Engineering Mathematics, Khanna, New Delhi, 2000.\n4. Jain R. K., Iyenger S.R.K., Advanced Engineering Mathematics, Narosa, 2002.\n5. Jain R. K., Iyenger S.R.K., Jain M.K., Numerical Methods for Scientific and Engineering Computation, New Age International Publishers, 2012.");
}
else if(o==6)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\tSEL\n-->some presentations\n -->some stories\n -->emotional learning\n -->social learningn ");}
else if(o==7)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\tEnglish Communication:\n-->letters\n-->email,cv\n -->communicational theory\n -->bookreview\n  ");}
else
{
    printf("invalid input!!!!!!!!");
}
printf("\n****************************************************************************************************************************\n");
printf ("=======================================================================================\n");
return 0;
}
 int route()
 {
    int y;
    printf ("\n=======================================================================================\n");
    printf("make sure connected to internet!!!!!!!!!\n");
     printf("\n****************************************************************************************************************************\n");

    printf("enter 1 by bus\n enter 2 by metro;");
    scanf("%d",&y);
    if (y==1)
    {
        system("start https://www.dtcbusroutes.in/bus/route/search/");

    }
    else
    {
            system("start https://www.delhimetrorail.com/map");
    }
    return 0;
 }

 
 int tim()
{
    int o;
    printf("enter 1:for pic\n2 for coa\n 3 for se\n 4 for it\n 5 for maths\n 6 for sel \n 7 for english:");
    scanf("%d",&o);
printf ("\n=======================================================================================\n");
if(o==1)
{
printf ("\t\t\t\t\t\t\t\t\t\tPIC class are as scheduled \n\t\t\t\t\t\t\t\t\t\tMonday-->9:30AM to 10: 30AM\n");
printf ("\t\t\t\t\t\t\t\t\t\tTuesday from 10:30AM to 11:30AM\n\t\t\t\t\t\t\t\t\t\tWednesday from 11:30AM to 12:30AM\n ");
printf ("\t\t\t\t\t\tPIC Lab is on Wednesday from 1:00to 3:00 PM\n");}
else if(o==2)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\t\t\tCOA Lab are as scheduled:- \n\t\t\t\t\t\t\t\t\t\tMonday-->1:00PM to 3: 00PM\n");
printf ("\t\t\t\t\t\t\t\t\t\tCOA classes are as:-\n\t\t\t\t\t\t\t\t\t\tMonday from 3:00PM to 4:00PM \n\t\t\t\t\t\t\t\t\t\tThursday from 2:00PM to 4:00PM\n");}
else if(o==3)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\t\t\tSE Lab are as scheduled:- \n\t\t\t\t\t\t\t\t\t\tThursday-->10:30AM to 12: 30PM\n");
printf ("\t\t\t\t\t\t\t\t\t\tSE classes are as scheduled:-\n\t\t\t\t\t\t\t\t\t\tThursday from 1:00PM to 2:00PM \n\t\t\t\t\t\t\t\t\t\tFriday from 1:00PM to 3:00PM\n");}
else if(o==4)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\t\t\tIT classes are as scheduled:-\n \t\t\t\t\t\t\t\t\t\tMonday from 8:30AM to 9:30AM \n\t\t\t\t\t\t\t\t\t\tTuesday from 8:30AM to 10:30AM\n");
printf ("\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\tIT Lab are as scheduled:- \n\t\t\t\t\t\t\t\t\t\tTuesday-->1:00PM to 3: 00PM\n");}
else if(o==5)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\tMaths class are as scheduled \n\t\t\t\t\t\t\t\t\t\t\nWednesday-->8:30AM to 10: 30AM\n");
printf ("\t\t\t\t\t\tThursday from 8:30AM to 10:30AM\n");}
else if(o==6)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\tSEL class are as scheduled \n\t\t\t\t\t\t\t\t\t\tWednesday from 10:30AM to 12: 30PM\n");}
else if(o==7)
{
printf("\n****************************************************************************************************************************\n");
printf ("\t\t\t\t\t\t\t\tEnglish Communication class are as scheduled \n\t\t\t\t\t\t\t\t\t\tFriday from 3:00PM to 5:00PM\n");}
else
{
    printf("invalid input!!!!!!!!");
}
printf("\n****************************************************************************************************************************\n");
printf ("=======================================================================================\n");
return 0;
}
int clubs()
{
    printf("->clubs running are:- \n->ABHIVYAKTI \n->FOTO-GRAFICA\n->ANTARA\n->NATRAJ\n->MAG-MA HOUSE\n");
    printf ("=======================================================================================\n");
    printf("sports are: badminton\n-->basket ball\n--> foot ball \n-->cricket \n");
    
    return 0;


}
int faculty()
{
    printf("COURSENAME ||FACULTY||   CONTACTNO.\n MATHEMATICS-I || PRATIBHA BHATT || 9650448508\n COA  || SHALLY KK  || 8920166739\n PIC  || KOMAL DHINGRA || 8585918359\nIT || ARUN DABAS ||9650XXXXXX\nSE  ||GURVINDER SINGH || 9212002599\nENG  ||REEMA DEVI || 7042915034.");
    return 0;

}
int handbook()
{
    system("start https://dseu.ac.in/wp-content/uploads/2022/06/dseu_handbook_2022.pdf");// "start" used for open url in windows

    return 0;
}
int facilities()
{
     printf("\n#################################################################################################################################\n"); 
        printf("list of facilities are:-\n ->students accessible wifi facilities.\n->student DTC bus pass.\n ->well maintained computer lab.\n ->actual visualisation with projector.");
        return 0;

}
int websites()
{
            printf("there are following websites:\n -->javapoint\n-->geeksforgeeks\n");
            return 0;
}
int main()
{
    char n[100];
    int N,c,a=2;
    printf("========================================================================================================================================\n");
    printf("\t\t\t\t\t\t\tenter YOUR name :");
    gets(n);
    printf("Hi! %s welcome to ARA's project here we are to help you to know about our DSEU dwarka campus\n",n);
    printf("how can i help you? please ener your choice to know about \n");
    printf("****************************************************************************************************************************\n");
    printf("1.Clubs running. \n2.Faculties. \n3.STUDENT HAND BOOK. \n4.timing of college.\n5.books preffered. \n6.student FACILITIES.\n7.search route for home or college\n8.students helping websitescourse related.\n");
     printf("========================================================================================================================================\n");
    printf("please enter your choice:");
    scanf("%d",&c);
    do{
       

       

    switch(c)
    {
        case 1 :clubs();
        break;
        case 2:faculty();
        break;
        case 3:handbook();
        break;
        case 4: tim();
        break;
        case 5: book();
        break;
        case 6:facilities();
        break;
        case 7:route();
        break;
        case 8:websites();
        break;
        default : printf(" OPTION WRONG");
        break;
        

        }
        printf("\n****************************************************************************************************************************\n");
        printf("enter 1. for stop\n 2. for again search.:");
        scanf("%d",&a);
        if (a==1)
        {
            break;
        }
        else
        {
        printf("1.Clubs running. \n2.Faculties. \n3.STUDENT HAND BOOK. \n4.timing of college.\n5.books preffered. \n6.student FACILITIES.\n7.search route for home or college\n8.students helping websitescourse related.\n");
        printf ("\n=======================================================================================\n");
        printf("please enter your choice:");
        scanf("%d",&c);
        
    }
    }while(a==2);


    

    return 0;
}
