\# Ishchenko Daria  
\#\#\# Front-end developer  

![Photo](/DashaPhoto.jpeg)
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

\#\#Contact  
\+54 9 11 6032 0596  
[ischenkodas@gmail.com](mailto:ischenkodas@gmail.com)  
\[Github\]([https://github.com/Habibon](https://github.com/Habibon))  
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

\#\#Education  
\#\#\#\#Lomonosov Moscow State University  
faculty of mechanics and mathematics

\#\#Courses  
\#\#\#\#QA-Engineering course  
Tinkoff bank, 2020

\#\#\#\#Yandex Algorithms marathon  
Yandex, 2023

\#\#\#\#Pega system architect  
Alfa-factory, 2024  
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

\#\#Skills  
\*Python(+Pandas, NumPy)  
\*HTML, CSS  
\*JS  
\*SQL  
\*Git  
\*Pega  
\*Debugging

\#\#Code Examples  
Calories counter  
\`\`\`

document.addEventListener('DOMContentLoaded', function(){  
    let usGender;  
    let activity;  
    let ans \= document.createElement('p');

        document.querySelectorAll('button.genderButton').forEach(button \=\> {  
            button.onclick \= function () {  
                this.classList.add('active');  
                usGender \= button.dataset.gender;  
            }  
        })  
          
      
        document.querySelectorAll('input\[type=radio\]').forEach(input \=\> {  
            input.onclick \= function () {  
                activity \= input.value;  
            }  
        })  
          
        document.getElementById('result').addEventListener('click', function(event) {  
          
            const usAge \= document.getElementById('age').value;  
            const usHeight \= document.getElementById('height').value;  
            const usWeight \= document.getElementById('weight').value;  
   
            if (usGender \=== 'male') {  
                ans.innerHTML \= Math.round((66.5 \+ 13.75 \* usWeight \+ 5.003 \* usHeight \- 6.775 \* usAge) \* activity);  
            }else{  
                ans.innerHTML \= Math.round((655.1 \+ 9.563 \* usWeight \+ 1.85 \* usHeight \- 4.676 \* usAge) \* activity);  
            }

            document.getElementById('answerform').appendChild(ans);  
            document.getElementById('answerform').style.display \= 'block';  
              
        });

        document.getElementById('clean').addEventListener('click', function(event) {  
            console.log('clean')

            document.getElementById('answerform').style.display \= "none";  
            document.querySelectorAll('button.genderButton').forEach(button \=\> {  
                button.classList.remove('active');  
            })

        })  
          
})  
\`\`\`

\#\#Languages  
English \- B1  
Spanish \- A2  
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

\#\#Work Experience  
\#\#\#Functional analysis lector  
Plekhanov Russian University of Economics  
2023  
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

I am a beginner front-end developer. I have experience in programming. Since I have a degree in fundamental mathematics, I took several courses at the university (C, Python, Coq). I have deep knowledge in such areas as the theory of algorithms and statistics. I sincerely believe that I can apply all this theory in practice, working as a programmer.

