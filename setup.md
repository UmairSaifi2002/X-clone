Deko y tailwind kaise app etup karogy
please gather all your attention

step1 :- 

      npm init -y

step2 :- 
      
      npm install -D tailwindcss@3

step3 :- npm tailwindcss init

step4 :- See this step specifies for this project only 

        if you want it for other projects go to the documentation of tailwindcss version 3
        the command for this project is

        First go the file tailwind.config.js
        with in  the content insert ["*html]

step5 :- for this project we creaate folder css within it we create input.css file with in which we write tailwind css code 
        
        @tailwind base;
        @tailwind components;
        @tailwind utilities;

step6 :- now paste this command
       
        "build": "npx tailwindcss -i ./css/input.css -o ./css/output.css --watch"
into the package.jon 
within the script block

step7 :- now go the index.html file
         and add 
         
         <link rel="stylesheet" href="/X-clone/css/output.css">

step8 :- now run the command 
        
        npm run build
