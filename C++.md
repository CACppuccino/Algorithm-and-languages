#C++ output

##output in style as float

 cout<<setiosflags(ios::fixed)<<setprecision(1)<<t;
 
##file stream  
###new object  
include <fstream>  
ifstream objectname("filename.txt"); //objectname can be anynames, e.g. fin  
so  
ifstream fin("filename.in");
fin>>a>>B>>c;  
ofstream fout("filname.out");
fout<<x<<y<<z;
