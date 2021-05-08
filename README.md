
## Immiguide

**Problem Statement** : 

After arriving in a foreign country many times immigrants face difficulties in securing the work, raising the children and accessing the services due to lack of knowledge of the procedure being followed on that land. Then they seek help on the web which takes many hours to find the relevant and best answers.

**Abstract** : 

To mitigate above stated problem build a web application to help the new immigrants to know about the procedure being followed to acquire a certain type of visa, SSN, etc. using the chatbot.

**Approach** :

The NLP model is pretained with the questions and answers asked previously related to the immigrations and procedure post landing in the US using the selected website scraping using python libraries BeautifulSoup, Scarpy. The user will ask the question using the chatbot and if that related question is previously asked then the NLP model will generate the response. If the question is very specific and unique or the user wants to know detailed procedure then the web app gives the list of experts resides in the nearby area the user can contact personally and can contact through on the same web platform. 

**Persona** :

Nonimmigrant student  

**Dataset** : 

Most of the frequently asked questions and answers can be found by scraping the Quota, Reddit etc.. . For the detailed or specific questions, the user will be contacted to the experts. 


## Project Architecture 


![image](https://user-images.githubusercontent.com/29173069/110276206-84304300-7f87-11eb-91a7-ba401b4346cc.png)

Screen Shot 2021-05-05 at 7.33.12 PM![image](https://user-images.githubusercontent.com/29173069/117520307-64ec6c80-af5c-11eb-91ba-dbbe4aea3ef3.png)

