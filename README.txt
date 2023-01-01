=============== CLIENT SIDE ==================
Create template for vanilla js
# npm create vite@latest client --template vanilla
select framework : Vanilla
select variant type : javascript 

cd to client directory
# npm install


Run client (on client directory)
# npm run dev

================ SERVER SIDE =====================
create server folder
cd to server folder
# npm init -y
# npm install cors dotenv express nodemon openai

create new file server.js
go to openai.com/api
to get apikey

go to menu Examples
type code, find "Natural language to OpenAI API"
open playground
choose code model "text-davinci-003" 
and then view code and paste on response body
change params prompt to our prompt from client

add param type module on package.json to allow import syntax instead of old require
add server nodemon on scripts

Run server (on server directory)
# npm run server 


===================== ROOT SIDE =============================
to upload to github repository on root dir 
add git ignore file  .gitignore

# git init 

