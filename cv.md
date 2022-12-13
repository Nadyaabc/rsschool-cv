  Personal Information  
Name: Nadya  

Surname: Zhoglo  

Nationality: Belarusian  

Phone number: +375 29 551-87-28 (mobile)  

Discord: nadzeyazhohla(nadyaabc)  

Email: nadyash295923@gmail.com  

Adress: 95 Dzerzhinskogo Prospect, apt. 817, Minsk, 220116, Belarus  

Marital status: single  

Date of birth: 30th Sept 2004  


Education  


Currently studying at Belarusian State University of Informatics and Radioelectrinics  

Expected to graduate in 2025  

Study programme: Automated Data Processing Systems  

Qualification: Information Technologies Engineer  



Special skills:  

Native Belarusian  

Native Russian  

Fluent English  



// Sort of the structure in alphabetical order  

	for (int i = 0; i < n + 1; i++)  
  
	{  
  
		for (int j = 1; j < n; j++)  
    
		{  
    
			if (strcmp(list[j - 1].name, list[j].name) > 0)  
      
			{  
      
				tmp = list[j - 1];  
        
				list[j - 1] = list[j];  
        
				list[j] = tmp;  
        
			}  
      
		}  
    
  }
